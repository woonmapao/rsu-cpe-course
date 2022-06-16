<script>
    let mat136 = false;
    let phy137 = false;
    let rsu183 = false;
    let rsu111 = false;
    let gen133 = false;
    let enl125 = false;
    let cpe218 = false;
    let cpe219 = false;
    let cpe161 = false;
    let mat137 = false;
    let enl126 = false;
    let rsu112 = false;
    let ge1 = false;
    let cpe263 = false;
    let cpe231 = false;
    let mat138 = false;
    let cpe221 = false;
    let ge2 = false;
    let lang1 = false;
    let cpe336 = false;
    let cpe337 = false;
    let cpe360 = false;
    let cpe222 = false;
    let ien221 = false;
    let ge3 = false;
    let lang2 = false;
    let cpe432 = false;
    let ien301 = false;
    let cpe362 = false;
    let cpe308 = false;
    let cpe332 = false;
    let cpe326 = false;
    let cpe327 = false;
    let cpe413 = false;
    let cpe414 = false;
    let cpe363 = false;
    let cpe441 = false;
    let cpe419 = false;
    let cpe426 = false;
    let cpe427 = false;
    let cpe490 = false;
    let cpe491 = false;
    let cpe4xx1 = false;
    let cpe4xx2 = false;
    let cpe4xx3 = false;
    let cpe492 = false;
    let ge4 = false;
    let free1 = false;
    let free2 = false;
    let gen494 = false;
</script>

<div class="container">
    <div class="row justify-content-center">
        <div
            class="col-sm-1 head fs-5 year11"
            on:click={() => {
                mat136 = true;
                phy137 = true;
                rsu183 = true;
                rsu111 = true;
                gen133 = true;
                gen133 = true;
                enl125 = true;
            }}
        >
            ปี 1 เทอม 1
        </div>
        <div
            class="col-sm-1 head fs-5 year12"
            on:click={() => {
                cpe218 = true;
                cpe219 = true;
                cpe161 = true;
                mat137 = true;
                enl126 = true;
                rsu112 = true;
                ge1 = true;
            }}
        >
            ปี 1 เทอม 2
        </div>
        <div
            class="col-sm-1 head fs-5 year21"
            on:click={() => {
                cpe263 = true;
                cpe231 = true;
                mat138 = true;
                cpe221 = true;
                ge2 = true;
                lang1 = true;
            }}
        >
            ปี 2 เทอม 1
        </div>
        <div
            class="col-sm-1 head fs-5 year22"
            on:click={() => {
                cpe336 = true;
                cpe337 = true;
                cpe360 = true;
                cpe222 = true;
                ien221 = true;
                ge3 = true;
                lang2 = true;
            }}
        >
            ปี 2 เทอม 2
        </div>
        <div
            class="col-sm-1 head fs-5 year31"
            on:click={() => {
                cpe432 = true;
                ien301 = true;
                cpe362 = true;
                cpe308 = true;
                cpe332 = true;
                cpe326 = true;
                cpe327 = true;
            }}
        >
            ปี 3 เทอม 1
        </div>
        <div
            class="col-sm-1 head fs-5 year32"
            on:click={() => {
                cpe413 = true;
                cpe414 = true;
                cpe363 = true;
                cpe441 = true;
                cpe419 = true;
                cpe426 = true;
                cpe427 = true;
            }}
        >
            ปี 3 เทอม 2
        </div>
        <div class="col-sm-1 head fs-5 year4s">ฤดูร้อน</div>
        <div class="col-sm-1 head fs-5 year41">ปี 4 เทอม 1</div>
        <div class="col-sm-1 head fs-5 year42">ปี 4 เทอม 2</div>
    </div>
    <div class="row justify-content-center">
        <div class="subject col-sm-1 fs-5 year11">
            <div
                class:mat136
                class:red={!mat136}
                class="mat136pos"
                on:click={() => (mat136 = !mat136)}
            >
                MAT136
            </div>
            <div
                class:phy137
                class:red={!phy137}
                class="phy137pos"
                on:click={() => (phy137 = !phy137)}
            >
                PHY137
            </div>
            <div
                class:rsu183
                class:red={!rsu183}
                class="rsu183pos"
                on:click={() => (rsu183 = !rsu183)}
            >
                RSU183
            </div>
            <div
                class:rsu111
                class:red={!rsu111}
                class="rsu111pos"
                on:click={() => (rsu111 = !rsu111)}
            >
                RSU111
            </div>
            <div
                class:gen133
                class:red={!gen133}
                class="gen133pos"
                on:click={() => (gen133 = !gen133)}
            >
                GEN133
            </div>
            <div
                class:enl125
                class:red={!enl125}
                class="enl125pos"
                on:click={() => (enl125 = !enl125)}
            >
                ENL125
            </div>
        </div>
        <div class="subject col-sm-1 fs-5 year12">
            <div
                class:unclickable={!mat136}
                class:cpe218
                class:red={!cpe218}
                class="cpe218pos"
                on:click={() => (cpe218 = !cpe218)}
            >
                CPE218
            </div>
            <div
                class:unclickable={!mat136}
                class:cpe219
                class:red={!cpe219}
                class="cpe219pos"
                on:click={() => (cpe219 = !cpe219)}
            >
                CPE219
            </div>
            <div
                class:cpe161
                class:red={!cpe161}
                class="cpe161pos"
                on:click={() => (cpe161 = !cpe161)}
            >
                CPE161
            </div>
            <div
                class:unclickable={!mat136}
                class:mat137
                class:red={!mat137}
                class="mat137pos"
                on:click={() => (mat137 = !mat137)}
            >
                MAT137
            </div>
            <div
                class:enl126
                class:red={!enl126}
                class="enl126pos"
                on:click={() => (enl126 = !enl126)}
            >
                ENL126
            </div>
            <div
                class:rsu112
                class:red={!rsu112}
                class="rsu112pos"
                on:click={() => (rsu112 = !rsu112)}
            >
                RSU112
            </div>
            <div
                class:ge1
                class:red={!ge1}
                class="ge1pos"
                on:click={() => (ge1 = !ge1)}
            >
                GE(3-7)
            </div>
        </div>
        <div class="subject col-sm-1 fs-5 year21">
            <div
                class:unclickable={!cpe161}
                class:cpe263
                class:red={!cpe263}
                class="cpe263pos"
                on:click={() => (cpe263 = !cpe263)}
            >
                CPE263
            </div>
            <div
                class:unclickable={!mat137}
                class:cpe231
                class:red={!cpe231}
                class="cpe231pos"
                on:click={() => (cpe231 = !cpe231)}
            >
                CPE231
            </div>
            <div
                class:unclickable={!mat137}
                class:mat138
                class:red={!mat138}
                class="mat138pos"
                on:click={() => (mat138 = !mat138)}
            >
                MAT138
            </div>
            <div
                class:unclickable={!mat136}
                class:cpe221
                class:red={!cpe221}
                class="cpe221pos"
                on:click={() => (cpe221 = !cpe221)}
            >
                CPE221
            </div>
            <div
                class:ge2
                class:red={!ge2}
                class="ge2pos"
                on:click={() => (ge2 = !ge2)}
            >
                GE(3-7)
            </div>
            <div
                class:lang1
                class:red={!lang1}
                class="lang1pos"
                on:click={() => (lang1 = !lang1)}
            >
                LANG1
            </div>
        </div>
        <div class="subject col-sm-1 fs-5 year22">
            <div
                class:unclickable={!cpe218}
                class:cpe336
                class:red={!cpe336}
                class="cpe336pos"
                on:click={() => (cpe336 = !cpe336)}
            >
                CPE336
            </div>
            <div
                class:unclickable={!cpe218}
                class:cpe337
                class:red={!cpe337}
                class="cpe337pos"
                on:click={() => (cpe337 = !cpe337)}
            >
                CPE337
            </div>
            <div
                class:unclickable={!cpe231}
                class:cpe360
                class:red={!cpe360}
                class="cpe360pos"
                on:click={() => (cpe360 = !cpe360)}
            >
                CPE360
            </div>
            <div
                class:unclickable={!cpe221}
                class:cpe222
                class:red={!cpe222}
                class="cpe222pos"
                on:click={() => (cpe222 = !cpe222)}
            >
                CPE222
            </div>
            <div
                class:ien221
                class:red={!ien221}
                class="ien221pos"
                on:click={() => (ien221 = !ien221)}
            >
                IEN221
            </div>
            <div
                class:ge3
                class:red={!ge3}
                class="ge3pos"
                on:click={() => (ge3 = !ge3)}
            >
                GE(3-7)
            </div>
            <div
                class:lang2
                class:red={!lang2}
                class="lang2pos"
                on:click={() => (lang2 = !lang2)}
            >
                LANG2
            </div>
        </div>
        <div class="subject col-sm-1 fs-5 year31">
            <div
                class:unclickable={!cpe218}
                class:cpe432
                class:red={!cpe432}
                class="cpe432pos"
                on:click={() => (cpe432 = !cpe432)}
            >
                CPE432
            </div>
            <div
                class:unclickable={!mat136}
                class:ien301
                class:red={!ien301}
                class="ien301pos"
                on:click={() => (ien301 = !ien301)}
            >
                IEN301
            </div>
            <div
                class:unclickable={!cpe360}
                class:cpe362
                class:red={!cpe362}
                class="cpe362pos"
                on:click={() => (cpe362 = !cpe362)}
            >
                CPE362
            </div>
            <div
                class:unclickable={!mat138}
                class:cpe308
                class:red={!cpe308}
                class="cpe308pos"
                on:click={() => (cpe308 = !cpe308)}
            >
                CPE308
            </div>
            <div
                class:unclickable={!mat138 || !ien221}
                class:cpe332
                class:red={!cpe332}
                class="cpe332pos"
                on:click={() => (cpe332 = !cpe332)}
            >
                CPE332
            </div>
            <div
                class:unclickable={!ien221}
                class:cpe326
                class:red={!cpe326}
                class="cpe326pos"
                on:click={() => (cpe326 = !cpe326)}
            >
                CPE326
            </div>
            <div
                class:unclickable={!ien221}
                class:cpe327
                class:red={!cpe327}
                class="cpe327pos"
                on:click={() => (cpe327 = !cpe327)}
            >
                CPE327
            </div>
        </div>
        <div class="subject col-sm-1 fs-5 year32">
            <div
                class:unclickable={!cpe218}
                class:cpe413
                class:red={!cpe413}
                class="cpe413pos"
                on:click={() => (cpe413 = !cpe413)}
            >
                CPE413
            </div>
            <div
                class:unclickable={!cpe218}
                class:cpe414
                class:red={!cpe414}
                class="cpe414pos"
                on:click={() => (cpe414 = !cpe414)}
            >
                CPE414
            </div>
            <div
                class:unclickable={!cpe263}
                class:cpe363
                class:red={!cpe363}
                class="cpe363pos"
                on:click={() => (cpe363 = !cpe363)}
            >
                CPE363
            </div>
            <div
                class:unclickable={!cpe263 || !cpe362}
                class:cpe441
                class:red={!cpe441}
                class="cpe441pos"
                on:click={() => (cpe441 = !cpe441)}
            >
                CPE441
            </div>
            <div
                class:unclickable={!cpe360}
                class:cpe419
                class:red={!cpe419}
                class="cpe419pos"
                on:click={() => (cpe419 = !cpe419)}
            >
                CPE419
            </div>
            <div
                class:unclickable={!cpe326}
                class:cpe426
                class:red={!cpe426}
                class="cpe426pos"
                on:click={() => (cpe426 = !cpe426)}
            >
                CPE426
            </div>
            <div
                class:unclickable={!cpe326}
                class:cpe427
                class:red={!cpe427}
                class="cpe427pos"
                on:click={() => (cpe427 = !cpe427)}
            >
                CPE427
            </div>
        </div>
        <div class="subject col-sm-1 fs-5 year4s">
            <div
                class:cpe490
                class:red={!cpe490}
                class="cpe490pos"
                on:click={() => (cpe490 = !cpe490)}
            >
                CPE490
            </div>
            <p>training</p>
            <p>or</p>
            <p>co-op</p>
            <div
                class:gen494
                class:red={!gen494}
                class="gen494pos"
                on:click={() => (gen494 = !gen494)}
            >
                GEN494
            </div>
        </div>
        <div class="subject col-sm-1 fs-5 year41">
            <div
                class:cpe491
                class:red={!cpe491}
                class="cpe491pos"
                on:click={() => (cpe491 = !cpe491)}
            >
                CPE491
            </div>
            <div
                class:cpe4xx1
                class:red={!cpe4xx1}
                class="cpe4xx1pos"
                on:click={() => (cpe4xx1 = !cpe4xx1)}
            >
                CPE4XX
            </div>
            <div
                class:cpe4xx2
                class:red={!cpe4xx2}
                class="cpe4xx2pos"
                on:click={() => (cpe4xx2 = !cpe4xx2)}
            >
                CPE4XX
            </div>
            <div
                class:ge4
                class:red={!ge4}
                class="ge4pos"
                on:click={() => (ge4 = !ge4)}
            >
                GE(3-7)
            </div>
        </div>
        <div class="subject col-sm-1 fs-5 year42">
            <div
                class:cpe492
                class:red={!cpe492}
                class="cpe492pos"
                on:click={() => (cpe492 = !cpe492)}
            >
                CPE492
            </div>
            <div
                class:cpe4xx3
                class:red={!cpe4xx3}
                class="cpe4xx3pos"
                on:click={() => (cpe4xx3 = !cpe4xx3)}
            >
                CPE4XX
            </div>
            <div
                class:free1
                class:red={!free1}
                class="free1pos"
                on:click={() => (free1 = !free1)}
            >
                Free1
            </div>
            <div
                class:free2
                class:red={!free2}
                class="free2pos"
                on:click={() => (free2 = !free2)}
            >
                Free2
            </div>
        </div>
    </div>
</div>

<style>
    .red {
        background-color: rgba(145, 13, 19, 0.4);
        border: #910d13;
        border-style: groove;
        border-width: 3px;
        font-weight: bold;
        height: 3rem;
        width: 6rem;
        user-select: none;
    }

    .red:hover {
        background-color: rgba(235, 227, 20, 0.4);
        border: #f46c0b;
        border-style: groove;
        border-width: 3px;
        cursor: pointer;
        font-weight: bold;
        height: 3rem;
        width: 6rem;
        user-select: none;
    }

    .unclickable {
        background-color: rgba(66, 66, 66, 0.4);
        border: #424242;
        border-style: groove;
        border-width: 3px;
        color: #424242;
        font-weight: bold;
        height: 3rem;
        pointer-events: none;
        width: 6rem;
    }

    .head {
        cursor: pointer;
        user-select: none;
    }

    .mat136,
    .phy137,
    .rsu183,
    .rsu111,
    .gen133,
    .enl125,
    .cpe218,
    .cpe219,
    .cpe161,
    .mat137,
    .enl126,
    .rsu112,
    .ge1,
    .cpe263,
    .cpe231,
    .mat138,
    .cpe221,
    .ge2,
    .lang1,
    .cpe336,
    .cpe337,
    .cpe360,
    .cpe222,
    .ien221,
    .ge3,
    .lang2,
    .cpe432,
    .ien301,
    .cpe362,
    .cpe308,
    .cpe332,
    .cpe326,
    .cpe327,
    .cpe413,
    .cpe414,
    .cpe363,
    .cpe441,
    .cpe419,
    .cpe426,
    .cpe427,
    .cpe490,
    .cpe491,
    .cpe4xx1,
    .cpe4xx2,
    .cpe4xx3,
    .cpe492,
    .ge4,
    .free1,
    .free2,
    .gen494 {
        background-color: rgba(97, 189, 92, 0.4);
        border: #61bd5c;
        border-style: groove;
        border-width: 3px;
        color: green;
        font-weight: bold;
        height: 3rem;
        pointer-events: none;
        width: 6rem;
        user-select: none;
    }

    .head.year11:hover,
    .head.year12:hover,
    .head.year21:hover,
    .head.year22:hover,
    .head.year31:hover,
    .head.year32:hover {
        background-color: rgba(97, 189, 92, 0.4);
    }

    .container {
        margin-top: 2rem;
        margin-bottom: 0;
        max-width: 60%;
    }

    .col-sm-1 {
        border: #614124;
        border-style: groove;
        border-width: 2px;
        width: 11%;
    }

    .subject {
        height: 40rem;
    }

    .mat136pos {
        margin-top: 10.8rem;
    }

    .phy137pos {
        margin-top: 5rem;
    }

    .rsu183pos {
        margin-top: 5.5rem;
    }

    .cpe218pos {
        margin-top: 0.7rem;
    }

    .cpe161pos {
        margin-top: 1rem;
    }

    .mat137pos {
        margin-top: 3rem;
    }

    .enl126pos {
        margin-top: 13.6rem;
    }

    .cpe263pos {
        margin-top: 7.75rem;
    }

    .cpe231pos {
        margin-top: 3rem;
    }

    .mat138pos {
        margin-top: 2rem;
    }

    .cpe221pos {
        margin-top: 1rem;
    }

    .ge2pos {
        margin-top: 7.5rem;
    }

    .cpe336pos,
    .cpe432pos {
        margin-top: 2.5rem;
    }

    .cpe360pos {
        margin-top: 7rem;
    }

    .cpe222pos {
        margin-top: 4.3rem;
    }

    .ien221pos,
    .cpe362pos {
        margin-top: 1rem;
    }

    .ge3pos {
        margin-top: 3.4rem;
    }

    .ien301pos {
        margin-top: 5rem;
    }

    .cpe308pos {
        margin-top: 1.2rem;
    }

    .cpe332pos {
        margin-top: 3.5rem;
    }

    .cpe326pos {
        margin-top: 1rem;
    }

    .cpe413pos {
        margin-top: 0.7rem;
    }

    .cpe363pos,
    .cpe419pos {
        margin-top: 1rem;
    }

    .cpe441pos {
        margin-top: 2rem;
    }

    .cpe426pos {
        margin-top: 9.5rem;
    }

    .cpe490pos {
        margin-top: 12rem;
    }

    .cpe491pos {
        margin-top: 0.7rem;
    }

    .cpe4xx1pos,
    .ge4pos,
    .cpe4xx3pos {
        margin-top: 2rem;
    }

    .cpe4xx2pos,
    .free2pos {
        margin-top: 1rem;
    }

    .cpe492pos {
        margin-top: 0.7rem;
    }

    .free1pos {
        margin-top: 6rem;
    }
</style>
