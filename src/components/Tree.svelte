<script>
    export let mat136 = false;
    export let phy137 = false;
    export let rsu183 = false;
    export let rsu111 = false;
    export let gen133 = false;
    export let enl125 = false;
    export let cpe218 = false;
    export let cpe219 = false;
    export let cpe161 = false;
    export let mat137 = false;
    export let enl126 = false;
    export let rsu112 = false;
    export let ge1 = false;
    export let cpe263 = false;
    export let cpe231 = false;
    export let mat138 = false;
    export let cpe221 = false;
    export let ge2 = false;
    export let lang1 = false;
    export let cpe336 = false;
    export let cpe337 = false;
    export let cpe360 = false;
    export let cpe222 = false;
    export let ien221 = false;
    export let ge3 = false;
    export let lang2 = false;
    export let cpe432 = false;
    export let ien301 = false;
    export let cpe362 = false;
    export let cpe308 = false;
    export let cpe332 = false;
    export let cpe326 = false;
    export let cpe327 = false;
    export let cpe413 = false;
    export let cpe414 = false;
    export let cpe363 = false;
    export let cpe441 = false;
    export let cpe419 = false;
    export let cpe426 = false;
    export let cpe427 = false;
    export let cpe490 = false;
    export let cpe491 = false;
    export let cpe4xx1 = false;
    export let cpe4xx2 = false;
    export let cpe4xx3 = false;
    export let cpe492 = false;
    export let ge4 = false;
    export let free1 = false;
    export let free2 = false;
</script>

<div class="container">
    <div class="row justify-content-center">
        <div class="col-sm-1 fs-5">เทอม 1 ปี 1</div>
        <div class="col-sm-1 fs-5">เทอม 1 ปี 2</div>
        <div class="col-sm-1 fs-5">เทอม 2 ปี 1</div>
        <div class="col-sm-1 fs-5">เทอม 2 ปี 2</div>
        <div class="col-sm-1 fs-5">เทอม 3 ปี 1</div>
        <div class="col-sm-1 fs-5">เทอม 3 ปี 2</div>
        <div class="col-sm-1 fs-5">ฤดูร้อน</div>
        <div class="col-sm-1 fs-5">เทอม 4 ปี 1</div>
        <div class="col-sm-1 fs-5">เทอม 4 ปี 2</div>
    </div>
    <div class="row justify-content-center">
        <div id="year11" class="subject col-sm-1 fs-5">
            <div
                class:mat136
                class:mini={!mat136}
                class="mat136pos"
                on:click={() => (mat136 = !mat136)}
            >
                MAT136
            </div>
            <div
                class:phy137
                class:mini={!phy137}
                class="phy137pos"
                on:click={() => (phy137 = !phy137)}
            >
                PHY137
            </div>
            <div
                class:rsu183
                class:mini={!rsu183}
                class="rsu183pos"
                on:click={() => (rsu183 = !rsu183)}
            >
                RSU183
            </div>
            <div
                class:rsu111
                class:mini={!rsu111}
                class="rsu111pos"
                on:click={() => (rsu111 = !rsu111)}
            >
                RSU111
            </div>
            <div
                class:gen133
                class:mini={!gen133}
                class="gen133pos"
                on:click={() => (gen133 = !gen133)}
            >
                GEN133
            </div>
            <div
                class:enl125
                class:mini={!enl125}
                class="enl125pos"
                on:click={() => (enl125 = !enl125)}
            >
                ENL125
            </div>
        </div>
        <div id="yaer12" class="subject col-sm-1 fs-5">
            <div
                class:cpe218
                class:mini={!cpe218}
                class="cpe218pos"
                on:click={() => (cpe218 = !cpe218)}
            >
                CPE218
            </div>
            <div
                class:cpe219
                class:mini={!cpe219}
                class="cpe219pos"
                on:click={() => (cpe219 = !cpe219)}
            >
                CPE219
            </div>
            <div
                class:cpe161
                class:mini={!cpe161}
                class="cpe161pos"
                on:click={() => (cpe161 = !cpe161)}
            >
                CPE161
            </div>
            <div
                class:mat137
                class:mini={!mat137}
                class="mat137pos"
                on:click={() => (mat137 = !mat137)}
            >
                MAT137
            </div>
            <div
                class:enl126
                class:mini={!enl126}
                class="enl126pos"
                on:click={() => (enl126 = !enl126)}
            >
                ENL126
            </div>
            <div
                class:rsu112
                class:mini={!rsu112}
                class="rsu112pos"
                on:click={() => (rsu112 = !rsu112)}
            >
                RSU112
            </div>
            <div
                class:ge1
                class:mini={!ge1}
                class="ge1pos"
                on:click={() => (ge1 = !ge1)}
            >
                GE (G.3-7)
            </div>
        </div>
        <div id="yaer21" class="subject col-sm-1 fs-5" />
        <div id="yaer22" class="subject col-sm-1 fs-5" />
        <div id="yaer31" class="subject col-sm-1 fs-5" />
        <div id="yaer32" class="subject col-sm-1 fs-5" />
        <div id="yaer4s" class="subject col-sm-1 fs-5" />
        <div id="yaer41" class="subject col-sm-1 fs-5" />
        <div id="yaer42" class="subject col-sm-1 fs-5" />
    </div>
</div>

<style>
    .mini {
        background-color: rgba(145, 13, 19, 0.4);
        border: #910d13;
        border-style: groove;
        border-width: 3px;
        font-weight: bold;
        height: 3rem;
        width: 6rem;
    }

    .mini:hover {
        background-color: rgba(235, 227, 20, 0.4);
        border: #ebe314;
        cursor: pointer;
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
    .free2 {
        background-color: rgba(97, 189, 92, 0.4);
        border: #61bd5c;
        border-style: groove;
        border-width: 3px;
        font-weight: bold;
        height: 3rem;
        width: 6rem;
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

    .mat136pos{
        margin-top: 10.8rem;
    }

    .phy137pos{
        margin-top: 5rem;
    }

    .rsu183pos{
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
</style>
