<template>
    <Page>
        <ActionBar>
            <Label text="Конвертор"/>
        </ActionBar>
        <StackLayout class="wrapper">
            <FlexboxLayout class="container-menu">
                <Button class="container-menu__link"> Масса </Button>
                <Button class="container-menu__link">Температура t°</Button>
                <Button class="container-menu__link"> Длинна </Button>
                <Button class="container-menu__link"> Площадь </Button>
                <Button class="container-menu__link">Энергия ↯</Button>
            </FlexboxLayout>
        </StackLayout>

    </Page>

</template>

<script>
  export default {
  };
</script>

<style lang="scss">
.wrapper {
    // background: linear-gradient(to bottom, #ffc9c6 50%, #e0e2ff 50%);
    height: 100%;
    padding-bottom: 2%;
}
Button {
    margin: 0;
    padding: 0;
}
.container-menu {
    margin-top: 40px;
    flex-wrap: wrap;
    justify-content: flex-start;

    &__link {
        color: #e0e2ff;
        background-color: #e41515;
        margin: 0;
        padding: 0;
        width: 43%;
        height: 11%;
    
        &:active {
            color: #e0e2ff;
        }
    }
}
</style>