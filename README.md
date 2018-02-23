# MY-Sass-Short
一种基于sass的样式全新写法，类似Emmet，极大提高工作效率！




例子：
`
.con-main {
    @include ss(() (p 40));
}
.buzou {
    @include ss(() (ho 60)(bgc #D9D9D9));
    & span {
        @include ss((db) (w 20%)(fz 16)(lh 60px)(c #fff)(tac)(pr 3%) (fl));
        &.wei {
            @include ss((c #fff)(bg #D9D9D9 "b4.png" r));
        }
        &.wei1 {
            @include ss((c #fff)(bgc #D9D9D9));
        }
        &.guo {
            @include ss((c #6873e4) ());
        }
        &.guo1 {
            @include ss((c #6873e4) (bg #CACFFF "b2.png" r));
        }
        &.guo2 {
            @include ss((c #6873e4) (bg #CACFFF "b1.png" r));
        }
        &.on {
            @include ss((bg #6873e4 "b3.png" r)(pr 20) (c #fff));
        }
        &.on1 {
            @include ss((bgc #6873e4)(pr 20) (c #fff));
        }
    }
}
.f-title {
    @include ss((h 86) (mt 40)(bgc #F7F7F7)(tac)(pt 20));
}
.tit-input {
    @include ss((w 40%)(h 44)(bdrs 0 41 41 0) (bd 1px solid #3a82da)(fl)(p 0 40 0 20)(fz 18)(bgc));
}
.tit-but {
    @include ss((w 10%)(zxw 150)(h 44)(bdrs 44 0 0 44)(bg #3a82da "but.png" 20 c)(ml 20%)(bd 0)(fl)(c #fff)(fz 18)(pl 50)(tal));
}
.filter {
    @include ss(() (mt 20)(bgc)(bgc #F7F7F7)(h auto)(p 15 0));
}
.xuanze-ce {
    @include ss(() (mt 20)(bgc)(bgc #F7F7F7)(h auto)(p 40 90));
}
.yuan-bb {
    @include ss(() (who 309 309)(bg "z18.png")(jzc)(cup));
    & em {
        @include ss((db) (wh 50 50)(bg "z18t.png")(jzc)(mt 75));
    }
    & span {
        @include ss((fz 21) (c #fff)(db)(lh 24px)(m 20 0));
    }
    & samp {
        @include ss((fz 18)(wh 93 35) (c #f88b8b)(db)(bgc #fff)(bdrs 34)(lh 35px)(jzc));
    }
}
.yuan-bb2 {
    @include ss(() (who 309 309)(bg "z19.png")(jzc)(cup));
    & em {
        @include ss((db) (wh 50 50)(bg "z19t.png")(jzc)(mt 75));
    }
    & span {
        @include ss((fz 21) (c #fff)(db)(lh 24px)(m 20 0)(tac));
    }
    & samp {
        @include ss((fz 18)(wh 93 35) (c #EBBA48)(db)(bgc #fff)(bdrs 34)(lh 35px)(jzc));
    }
}
`
