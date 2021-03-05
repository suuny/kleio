<script>
    import UI_Header from "./components/UI_Header.svelte";
    import UI_Footer from "./components/UI_Footer.svelte";
</script>

<div class="App">
    <UI_Header/>

    <div class="form-center">
        <div class="input-center border-class-1">
            <div class="input-text-i158252 valign-text-middle roboto-normal-celeste-14px">email</div>
        </div>
        <div class="input-center-1 border-class-1">
            <div class="input-text-i158252 valign-text-middle roboto-normal-celeste-14px">password</div>
        </div>
        <div class="button-fill">
            <img class="vector" src=""/>
            <div class="label-i1582521692 valign-text-middle notosanskr-bold-white-14px">SIGN IN</div>
        </div>
    </div>

    <UI_Footer/>
</div>

<style>
    .App {
        width: 100%;
        max-width: 420px;
        margin: 0 auto;
        display: flex;
        min-height: 100%;
        flex-flow: column;
        align-items: stretch;

    }

    @import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
    @import url("https://fonts.googleapis.com/css?family=Roboto:400|Noto+Sans+KR:700,400");

    * {
        box-sizing: border-box;
    }

    .border-class-1 {
        border: 1px solid rgba(0, 0, 0, 1);
    }

    .button-fill {
        align-items: center;
        background-color: var(--cerulean);
        border-radius: 5px;
        display: flex;
        height: 36px;
        justify-content: flex-end;
        margin-top: 8px;
        min-width: 351px;
        padding: 0 135.5px;
    }

    .form-center {
        align-items: center;
        background-color: white;
        display: flex;
        flex-direction: column;
        height: 132px;
        padding: 4px 0;
        flex: 1;
    }

    .input-center {
        align-items: center;
        background-color: white;
        border-radius: 5px;
        display: flex;
        height: 36px;
        justify-content: flex-end;
        min-width: 351px;
        padding: 0 2px;
    }

    .input-center-1 {
        align-items: center;
        background-color: white;
        border-radius: 5px;
        display: flex;
        height: 36px;
        justify-content: flex-end;
        margin-top: 8px;
        min-width: 351px;
        padding: 0 2px;
    }

    .input-text-i158252 {
        height: 20px;
        letter-spacing: 0px;
        line-height: 20px;
        min-height: 20px;
        text-align: center;
        white-space: nowrap;
        width: 345px;
    }

    .label-i1582521692 {
        height: 20px;
        letter-spacing: 0px;
        line-height: 20px;
        margin-left: 6px;
        min-height: 20px;
        min-width: 55px;
        white-space: nowrap;
    }

    .notosanskr-bold-white-14px {
        color: white;
        font-family: "Noto Sans KR", Helvetica;
        font-size: 14px;
        font-style: normal;
        font-weight: 700;
    }

    .roboto-normal-celeste-14px {
        color: var(--celeste);
        font-family: "Roboto", Helvetica;
        font-size: 14px;
        font-style: normal;
        font-weight: 400;
    }

    .vector {
        height: 16px;
        width: 15px;
    }

    :root {
        --celeste: rgba(204, 204, 204, 1);
        --cerulean: rgba(0, 155, 224, 1);
    }

    .valign-text-middle {
        display: flex;
        flex-direction: column;
        justify-content: center;
    }

</style>