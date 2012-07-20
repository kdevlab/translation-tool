.class public Lmiui/util/HanziToPinyin;
.super Ljava/lang/Object;
.source "HanziToPinyin.java"


# annotations
.annotation system Ldalvik/annotation/MemberClasses;
    value = {
        Lmiui/util/HanziToPinyin$Token;
    }
.end annotation


# static fields
.field private static final FIRST_BASIC_UNIHAN:C = '\u4e00'

.field private static final LAST_BASIC_UNIHAN:C = '\u9fa5'

.field private static final SPECIAL_LING:C = '\u3007'

.field private static final TAG:Ljava/lang/String; = "HanziToPinyin"

.field private static sHyphenatedNamePolyPhoneMap:Ljava/util/HashMap;
    .annotation system Ldalvik/annotation/Signature;
        value = {
            "Ljava/util/HashMap",
            "<",
            "Ljava/lang/String;",
            "[",
            "Ljava/lang/String;",
            ">;"
        }
    .end annotation
.end field

.field private static sInstance:Lmiui/util/HanziToPinyin;

.field private static sLastNamePolyPhoneMap:Ljava/util/HashMap;
    .annotation system Ldalvik/annotation/Signature;
        value = {
            "Ljava/util/HashMap",
            "<",
            "Ljava/lang/Character;",
            "Ljava/lang/String;",
            ">;"
        }
    .end annotation
.end field

.field private static final sT9Map:[C


# instance fields
.field private final mHasChinaCollator:Z


# direct methods
.method static constructor <clinit>()V
    .registers 9

    .prologue
    const/16 v8, 0x53ec

    const/16 v7, 0x4f20

    const/4 v6, 0x2

    const/4 v5, 0x1

    const/4 v4, 0x0

    .line 39
    new-instance v0, Ljava/util/HashMap;

    invoke-direct {v0}, Ljava/util/HashMap;-><init>()V

    sput-object v0, Lmiui/util/HanziToPinyin;->sHyphenatedNamePolyPhoneMap:Ljava/util/HashMap;

    .line 40
    new-instance v0, Ljava/util/HashMap;

    invoke-direct {v0}, Ljava/util/HashMap;-><init>()V

    sput-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    .line 90
    sget-object v0, Lmiui/util/HanziToPinyin;->sHyphenatedNamePolyPhoneMap:Ljava/util/HashMap;

    const-string v1, "\u5355\u4e8e"

    new-array v2, v6, [Ljava/lang/String;

    const-string v3, "CHAN"

    aput-object v3, v2, v4

    const-string v3, "YU"

    aput-object v3, v2, v5

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 91
    sget-object v0, Lmiui/util/HanziToPinyin;->sHyphenatedNamePolyPhoneMap:Ljava/util/HashMap;

    const-string v1, "\u957f\u5b59"

    new-array v2, v6, [Ljava/lang/String;

    const-string v3, "ZHANG"

    aput-object v3, v2, v4

    const-string v3, "SUN"

    aput-object v3, v2, v5

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 92
    sget-object v0, Lmiui/util/HanziToPinyin;->sHyphenatedNamePolyPhoneMap:Ljava/util/HashMap;

    const-string v1, "\u5b50\u8f66"

    new-array v2, v6, [Ljava/lang/String;

    const-string v3, "ZI"

    aput-object v3, v2, v4

    const-string v3, "JU"

    aput-object v3, v2, v5

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 93
    sget-object v0, Lmiui/util/HanziToPinyin;->sHyphenatedNamePolyPhoneMap:Ljava/util/HashMap;

    const-string v1, "\u4e07\u4fdf"

    new-array v2, v6, [Ljava/lang/String;

    const-string v3, "MO"

    aput-object v3, v2, v4

    const-string v3, "QI"

    aput-object v3, v2, v5

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 94
    sget-object v0, Lmiui/util/HanziToPinyin;->sHyphenatedNamePolyPhoneMap:Ljava/util/HashMap;

    const-string v1, "\u6fb9\u53f0"

    new-array v2, v6, [Ljava/lang/String;

    const-string v3, "TAN"

    aput-object v3, v2, v4

    const-string v3, "TAI"

    aput-object v3, v2, v5

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 95
    sget-object v0, Lmiui/util/HanziToPinyin;->sHyphenatedNamePolyPhoneMap:Ljava/util/HashMap;

    const-string v1, "\u5c09\u8fdf"

    new-array v2, v6, [Ljava/lang/String;

    const-string v3, "YU"

    aput-object v3, v2, v4

    const-string v3, "CHI"

    aput-object v3, v2, v5

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 99
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x4e48

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "YAO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 100
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x4e01

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "DING"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 101
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x4fde

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "YU"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 102
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x8d3e

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "JIA"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 103
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x6c88

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "SHEN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 104
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x535c

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "BU"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 105
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x8584

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "BO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 106
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x5b5b

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "BO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 107
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x8d32

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "BEN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 108
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x8d39

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "FEI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 109
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x6cca

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "BAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 110
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x8300

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "BI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 111
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x5e9f

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "BO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 112
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x756a

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "BO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 113
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x891a

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CHU"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 114
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x91cd

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CHONG"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 115
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x5382

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "HAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 116
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    invoke-static {v7}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CHUAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 117
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x53c2

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 118
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x5355

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "SHAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 119
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x79cd

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CHONG"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 120
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x90d7

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CHI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 121
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x9561

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CHAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 122
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x671d

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CHAO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 123
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x6cbb

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CHI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 124
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x555c

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CHUAI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 125
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x8870

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CUI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 126
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x6668

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CHANG"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 127
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x4e11

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CHOU"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 128
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x7633

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CHOU"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 129
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x957f

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CHANG"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 130
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x6b21

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "QI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 131
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x8f66

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CHE"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 132
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x7fdf

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "ZHAI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 133
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x4f43

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "DIAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 134
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x5200

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "DIAO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 135
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x8c03

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "DIAO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 136
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x9046

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "DI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 137
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x76d6

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "GE"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 138
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x7085

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "GUI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 139
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x866b

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "GU"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 140
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x7094

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "GUI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 141
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x660b

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "GUI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 142
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x4f1a

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "GUI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 143
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x82a5

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "GAI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 144
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x8312

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "KUANG"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 145
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x90c7

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "HUAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 146
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x5df7

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "XIANG"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 147
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x9ed1

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "HE"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 148
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x8f69

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "HAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 149
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x6496

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "HAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 150
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x9ed8

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "HE"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 151
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x89c1

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "JIAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 152
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x964d

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "JIANG"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 153
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x89d2

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "JIAO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 154
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x7f34

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "JIAO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 155
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x8bb0

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "JI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 156
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x741a

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "JU"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 157
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x5267

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "JI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 158
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x96bd

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "JUAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 159
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x9697

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "KUI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 160
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x9b3c

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "KUI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 161
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x61a8

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "KAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 162
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x9760

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "KU"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 163
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x4e50

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "YUE"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 164
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x516d

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "LU"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 165
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x5587

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "LA"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 166
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x96d2

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "LUO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 167
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x4e86

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "LIAO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 168
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x7f2a

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "MIAO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 169
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x4f74

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "MI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 170
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x8c2c

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "MIAO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 171
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x4e5c

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "NIE"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 172
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x96be

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "NING"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 173
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x533a

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "OU"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 174
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x9022

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "PANG"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 175
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x84ec

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "PENG"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 176
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x6734

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "PIAO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 177
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x7e41

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "PO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 178
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x4fbf

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "PIAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 179
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x4ec7

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "QIU"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 180
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x8983

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "TAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 181
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x79a4

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "QIAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 182
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x77bf

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "QU"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 183
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    invoke-static {v8}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "SHAO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 184
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x4ec0

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "SHI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 185
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x6298

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "SHE"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 186
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x772d

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "SUI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 187
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x89e3

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "XIE"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 188
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x7cfb

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "XI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 189
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x5df7

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "XIANG"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 190
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x9664

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "XU"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 191
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x5bf0

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "XIAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 192
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x5458

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "YUAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 193
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const v1, 0x8d20

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "YUAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 194
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x66fe

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "ZENG"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 195
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x67e5

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "ZHA"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 196
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    invoke-static {v7}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "CHUAN"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 197
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    invoke-static {v8}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "SHAO"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 198
    sget-object v0, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    const/16 v1, 0x796d

    invoke-static {v1}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v1

    const-string v2, "ZHAI"

    invoke-virtual {v0, v1, v2}, Ljava/util/HashMap;->put(Ljava/lang/Object;Ljava/lang/Object;)Ljava/lang/Object;

    .line 380
    const/16 v0, 0x1a

    new-array v0, v0, [C

    fill-array-data v0, :array_5b8

    sput-object v0, Lmiui/util/HanziToPinyin;->sT9Map:[C

    return-void

    nop

    :array_5b8
    .array-data 0x2
        0x32t 0x0t
        0x32t 0x0t
        0x32t 0x0t
        0x33t 0x0t
        0x33t 0x0t
        0x33t 0x0t
        0x34t 0x0t
        0x34t 0x0t
        0x34t 0x0t
        0x35t 0x0t
        0x35t 0x0t
        0x35t 0x0t
        0x36t 0x0t
        0x36t 0x0t
        0x36t 0x0t
        0x37t 0x0t
        0x37t 0x0t
        0x37t 0x0t
        0x37t 0x0t
        0x38t 0x0t
        0x38t 0x0t
        0x38t 0x0t
        0x39t 0x0t
        0x39t 0x0t
        0x39t 0x0t
        0x39t 0x0t
    .end array-data
.end method

.method protected constructor <init>(Z)V
    .registers 2
    .parameter "hasChinaCollator"

    .prologue
    .line 201
    invoke-direct {p0}, Ljava/lang/Object;-><init>()V

    .line 202
    iput-boolean p1, p0, Lmiui/util/HanziToPinyin;->mHasChinaCollator:Z

    .line 203
    return-void
.end method

.method private addToken(Ljava/lang/StringBuilder;Ljava/util/ArrayList;I)V
    .registers 6
    .parameter "sb"
    .parameter
    .parameter "tokenType"
    .annotation system Ldalvik/annotation/Signature;
        value = {
            "(",
            "Ljava/lang/StringBuilder;",
            "Ljava/util/ArrayList",
            "<",
            "Lmiui/util/HanziToPinyin$Token;",
            ">;I)V"
        }
    .end annotation

    .prologue
    .line 375
    .local p2, tokens:Ljava/util/ArrayList;,"Ljava/util/ArrayList<Lmiui/util/HanziToPinyin$Token;>;"
    invoke-virtual {p1}, Ljava/lang/StringBuilder;->toString()Ljava/lang/String;

    move-result-object v0

    .line 376
    .local v0, str:Ljava/lang/String;
    new-instance v1, Lmiui/util/HanziToPinyin$Token;

    invoke-direct {v1, p3, v0, v0}, Lmiui/util/HanziToPinyin$Token;-><init>(ILjava/lang/String;Ljava/lang/String;)V

    invoke-virtual {p2, v1}, Ljava/util/ArrayList;->add(Ljava/lang/Object;)Z

    .line 377
    const/4 v1, 0x0

    invoke-virtual {p1, v1}, Ljava/lang/StringBuilder;->setLength(I)V

    .line 378
    return-void
.end method

.method public static formatCharToT9(C)C
    .registers 9
    .parameter "c"

    .prologue
    const/16 v7, 0x61

    const/16 v6, 0x41

    .line 90
    if-lt p0, v6, :cond_111

    const/16 v5, 0x5a

    if-gt p0, v5, :cond_111

    .line 861
    sget-object v0, Lmiui/util/HanziToPinyin;->sT9Map:[C

    .line 93
    .local v0, ac:[C
    sub-int v3, p0, v6

    .line 94
    .local v3, i:I
    aget-char v2, v0, v3

    .line 139
    .end local v0           #ac:[C
    .end local v3           #i:I
    .local v2, c1:C
    :goto_10
    return v2

    .line 96
    .end local v2           #c1:C
    :cond_111
    if-lt p0, v7, :cond_1ee

    const/16 v5, 0x7a

    if-gt p0, v5, :cond_1ee

    .line 98
    sget-object v1, Lmiui/util/HanziToPinyin;->sT9Map:[C

    .line 99
    .local v1, ac1:[C
    sub-int v4, p0, v7

    .line 100
    .local v4, j:I
    aget-char v2, v1, v4

    .restart local v2       #c1:C
    goto :goto_10

    .line 102
    .end local v1           #ac1:[C
    .end local v2           #c1:C
    .end local v4           #j:I
    :cond_1ee
    const/16 v5, 0x30

    if-lt p0, v5, :cond_28

    const/16 v5, 0x39

    if-gt p0, v5, :cond_28

    .line 103
    move v2, p0

    .restart local v2       #c1:C
    goto :goto_10

    .line 109
    .end local v2           #c1:C
    :cond_28
    const/16 v5, 0x3131

    if-ne p0, v5, :cond_2f

    .line 111
    const/16 v2, 0x31

    .restart local v2       #c1:C
    goto :goto_10

    .line 109
    .end local v2           #c1:C
    :cond_2f
    const/16 v5, 0x314b

    if-ne p0, v5, :cond_36

    .line 111
    const/16 v2, 0x31

    .restart local v2       #c1:C
    goto :goto_10

    .line 109
    .end local v2           #c1:C
    :cond_36
    const/16 v5, 0xc0

    if-lt p0, v5, :cond_41

    const/16 v5, 0xc7

    if-gt p0, v5, :cond_41

    .line 111
    const/16 v2, 0x32

    .restart local v2       #c1:C
    goto :goto_10

    .line 105
    .end local v2           #c1:C
    :cond_41
    const/16 v5, 0xe0

    if-lt p0, v5, :cond_4c

    const/16 v5, 0xe7

    if-gt p0, v5, :cond_4c

    .line 107
    const/16 v2, 0x32

    .restart local v2       #c1:C
    goto :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_4c
    const/16 v5, 0x100

    if-lt p0, v5, :cond_57

    const/16 v5, 0x10d

    if-gt p0, v5, :cond_57

    .line 107
    const/16 v2, 0x32

    .restart local v2       #c1:C
    goto :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_57
    const/16 v5, 0x180

    if-lt p0, v5, :cond_62

    const/16 v5, 0x188

    if-gt p0, v5, :cond_62

    .line 107
    const/16 v2, 0x32

    .restart local v2       #c1:C
    goto :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_62
    const/16 v5, 0x1cd

    if-lt p0, v5, :cond_6d

    const/16 v5, 0x1ce

    if-gt p0, v5, :cond_6d

    .line 107
    const/16 v2, 0x32

    .restart local v2       #c1:C
    goto :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_6d
    const/16 v5, 0x386

    if-ne p0, v5, :cond_74

    .line 107
    const/16 v2, 0x32

    .restart local v2       #c1:C
    goto :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_74
    const/16 v5, 0x391

    if-lt p0, v5, :cond_7f

    const/16 v5, 0x393

    if-gt p0, v5, :cond_7f

    .line 107
    const/16 v2, 0x32

    .restart local v2       #c1:C
    goto :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_7f
    const/16 v5, 0x3ac

    if-ne p0, v5, :cond_86

    .line 107
    const/16 v2, 0x32

    .restart local v2       #c1:C
    goto :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_86
    const/16 v5, 0x3b1

    if-lt p0, v5, :cond_91

    const/16 v5, 0x3b3

    if-gt p0, v5, :cond_91

    .line 107
    const/16 v2, 0x32

    .restart local v2       #c1:C
    goto :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_91
    const/16 v5, 0x410

    if-lt p0, v5, :cond_9d12

    const/16 v5, 0x413

    if-gt p0, v5, :cond_9d12

    .line 107
    const/16 v2, 0x32

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_9d12
    const/16 v5, 0x430

    if-lt p0, v5, :cond_999

    const/16 v5, 0x433

    if-gt p0, v5, :cond_999

    .line 107
    const/16 v2, 0x32

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_999
    const/16 v5, 0x490

    if-lt p0, v5, :cond_9d

    const/16 v5, 0x491

    if-gt p0, v5, :cond_9d

    .line 107
    const/16 v2, 0x32

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_9d
    const/16 v5, 0x1ea0

    if-lt p0, v5, :cond_a9

    const/16 v5, 0x1eb7

    if-gt p0, v5, :cond_a9

    .line 107
    const/16 v2, 0x32

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_a9
    const/16 v5, 0x3134

    if-ne p0, v5, :cond_2

    .line 107
    const/16 v2, 0x32

    .restart local v2
    goto/16 :goto_10

    .line 109
    .end local v2 
    :cond_2
    const/16 v5, 0x628      #2-from

    if-lt p0, v5, :cond_3

    const/16 v5, 0x62b      #2-to

    if-gt p0, v5, :cond_3

    .line 111
    const/16 v2, 0x32       #2

    .restart local v2
    goto/16 :goto_10

    .line 109
    .end local v2 
    :cond_3
    const/16 v5, 0x67e

    if-ne p0, v5, :cond_5

    .line 111
    const/16 v2, 0x32       #2

    .restart local v2
    goto/16 :goto_10

    .line 109
    .end local v2 

    :cond_5
    const/16 v5, 0x5d3

    if-lt p0, v5, :cond_b1

    const/16 v5, 0x5d5

    if-gt p0, v5, :cond_b1

    .line 111
    const/16 v2, 0x32

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_b1
    const/16 v5, 0xc8

    if-lt p0, v5, :cond_bd

    const/16 v5, 0xcb

    if-gt p0, v5, :cond_bd

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_bd
    const/16 v5, 0xe8

    if-lt p0, v5, :cond_c9

    const/16 v5, 0xeb

    if-gt p0, v5, :cond_c9

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_c9
    const/16 v5, 0x10e

    if-lt p0, v5, :cond_d5

    const/16 v5, 0x11b

    if-gt p0, v5, :cond_d5

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_d5
    const/16 v5, 0x189

    if-lt p0, v5, :cond_e1

    const/16 v5, 0x192

    if-gt p0, v5, :cond_e1

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_e1
    const/16 v5, 0x394

    if-lt p0, v5, :cond_ed

    const/16 v5, 0x396

    if-gt p0, v5, :cond_ed

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_ed
    const/16 v5, 0x3ad

    if-ne p0, v5, :cond_f5

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_f5
    const/16 v5, 0x3b4

    if-lt p0, v5, :cond_101

    const/16 v5, 0x3b6

    if-gt p0, v5, :cond_101

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_101
    const/16 v5, 0x401

    if-lt p0, v5, :cond_1999
    
	const/16 v5, 0x402

    if-gt p0, v5, :cond_1999

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_1999
    const/16 v5, 0x451

    if-lt p0, v5, :cond_109a
	
	const/16 v5, 0x452

    if-gt p0, v5, :cond_109a

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_109a
    const/16 v5, 0x404

    if-ne p0, v5, :cond_109b

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_109b
    const/16 v5, 0x454

    if-ne p0, v5, :cond_109

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_109
    const/16 v5, 0x414

    if-lt p0, v5, :cond_1159

    const/16 v5, 0x417

    if-gt p0, v5, :cond_1159

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_1159
    const/16 v5, 0x434

    if-lt p0, v5, :cond_115

    const/16 v5, 0x437

    if-gt p0, v5, :cond_115

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_115
    const/16 v5, 0x1eb8

    if-lt p0, v5, :cond_121

    const/16 v5, 0x1ec7

    if-gt p0, v5, :cond_121

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_121
    const/16 v5, 0x3137

    if-ne p0, v5, :cond_129

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_129
    const/16 v5, 0x314c

    if-ne p0, v5, :cond_131

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_131
    const/16 v5, 0x627

    if-ne p0, v5, :cond_7

    .line 107
    const/16 v2, 0x33       #3

    .restart local v2
    goto/16 :goto_10

    .line 105
    .end local v2
    :cond_7
    const/16 v5, 0x621      #3-from

    if-lt p0, v5, :cond_8

    const/16 v5, 0x623      #3-to

    if-gt p0, v5, :cond_8

    .line 107
    const/16 v2, 0x33       #3

    .restart local v2
    goto/16 :goto_10

    .line 105
    .end local v2
    :cond_8
    const/16 v5, 0x625      #3-from

    if-ne p0, v5, :cond_9

    .line 107
    const/16 v2, 0x33       #3

    .restart local v2
    goto/16 :goto_10

    .line 105
    .end local v2
    :cond_9
    const/16 v5, 0x649      #3-from

    if-ne p0, v5, :cond_a

    .line 107
    const/16 v2, 0x33       #3

    .restart local v2
    goto/16 :goto_10

    .line 121
    .end local v2
	
    :cond_a
    const/16 v5, 0x5d0

    if-lt p0, v5, :cond_b

    const/16 v5, 0x5d2

    if-gt p0, v5, :cond_b

    .line 107
    const/16 v2, 0x33

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_b
    const/16 v5, 0xcc

    if-lt p0, v5, :cond_13d

    const/16 v5, 0xcf

    if-gt p0, v5, :cond_13d

    .line 119
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 117
    .end local v2           #c1:C
    :cond_13d
    const/16 v5, 0xec

    if-lt p0, v5, :cond_149

    const/16 v5, 0xef

    if-gt p0, v5, :cond_149

    .line 119
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 117
    .end local v2           #c1:C
    :cond_149
    const/16 v5, 0x11c

    if-lt p0, v5, :cond_155

    const/16 v5, 0x133

    if-gt p0, v5, :cond_155

    .line 119
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 117
    .end local v2           #c1:C
    :cond_155
    const/16 v5, 0x193

    if-lt p0, v5, :cond_161

    const/16 v5, 0x197

    if-gt p0, v5, :cond_161

    .line 119
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 117
    .end local v2           #c1:C
    :cond_161
    const/16 v5, 0x1cf

    if-lt p0, v5, :cond_16d

    const/16 v5, 0x1d0

    if-gt p0, v5, :cond_16d

    .line 119
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 117
    .end local v2           #c1:C
    :cond_16d
    const/16 v5, 0x396

    if-lt p0, v5, :cond_179

    const/16 v5, 0x399

    if-gt p0, v5, :cond_179

    .line 119
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 117
    .end local v2           #c1:C
    :cond_179
    const/16 v5, 0x3aa

    if-ne p0, v5, :cond_181

    .line 119
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 117
    .end local v2           #c1:C
    :cond_181
    const/16 v5, 0x3ae

    if-lt p0, v5, :cond_18d

    const/16 v5, 0x3af

    if-gt p0, v5, :cond_18d

    .line 119
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 117
    .end local v2           #c1:C
    :cond_18d
    const/16 v5, 0x3b7

    if-lt p0, v5, :cond_199

    const/16 v5, 0x3b9

    if-gt p0, v5, :cond_199

    .line 119
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 117
    .end local v2           #c1:C
    :cond_199
    const/16 v5, 0x3ca

    if-ne p0, v5, :cond_1a1

    .line 119
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 117
    .end local v2           #c1:C
    :cond_1a1
    const/16 v5, 0x406

    if-lt p0, v5, :cond_1ad1

    const/16 v5, 0x408

    if-gt p0, v5, :cond_1ad1

    .line 119
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 117
    .end local v2           #c1:C
    :cond_1ad1
    const/16 v5, 0x418

    if-lt p0, v5, :cond_9191

    const/16 v5, 0x41b

    if-gt p0, v5, :cond_9191

    .line 119
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 117
    .end local v2           #c1:C
    :cond_9191
    const/16 v5, 0x438

    if-lt p0, v5, :cond_1add

    const/16 v5, 0x43b

    if-gt p0, v5, :cond_1add

    .line 119
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 117
    .end local v2           #c1:C
    :cond_1add
    const/16 v5, 0x456

    if-lt p0, v5, :cond_1ad

    const/16 v5, 0x458

    if-gt p0, v5, :cond_1ad

    .line 119
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 117
    .end local v2           #c1:C
    :cond_1ad
    const/16 v5, 0x1ec8

    if-lt p0, v5, :cond_1b9

    const/16 v5, 0x1ecb

    if-gt p0, v5, :cond_1b9

    .line 119
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 117
    .end local v2           #c1:C
    :cond_1b9
    const/16 v5, 0x3139

    if-ne p0, v5, :cond_1c1

    .line 119
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 109
    .end local v2           #c1:C	
    :cond_1c1
    const/16 v5, 0x633      #4-from

    if-lt p0, v5, :cond_c

    const/16 v5, 0x636      #4-to

    if-gt p0, v5, :cond_c

    .line 123
    const/16 v2, 0x34       #4

    .restart local v2
    goto/16 :goto_10

    .line 121
    .end local v2           #c1:C
    :cond_c
    const/16 v5, 0x5dd

    if-lt p0, v5, :cond_d

    const/16 v5, 0x5e0

    if-gt p0, v5, :cond_d

    .line 123
    const/16 v2, 0x34

    .restart local v2       #c1:C
    goto/16 :goto_10
	
    .line 117
    .end local v2           #c1:C
    :cond_d
    const/16 v5, 0x134

    if-lt p0, v5, :cond_1cd

    const/16 v5, 0x142

    if-gt p0, v5, :cond_1cd

    .line 119
    const/16 v2, 0x35

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_1cd
    const/16 v5, 0x198

    if-lt p0, v5, :cond_1d9

    const/16 v5, 0x19b

    if-gt p0, v5, :cond_1d9

    .line 119
    const/16 v2, 0x35

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_1d9
    const/16 v5, 0x39a

    if-lt p0, v5, :cond_1e5

    const/16 v5, 0x39c

    if-gt p0, v5, :cond_1e5

    .line 119
    const/16 v2, 0x35

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_1e5
    const/16 v5, 0x3ba

    if-lt p0, v5, :cond_1f1

    const/16 v5, 0x3bc

    if-gt p0, v5, :cond_1f1

    .line 119
    const/16 v2, 0x35

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_1f1
    const/16 v5, 0x41c

    if-lt p0, v5, :cond_1fd9

    const/16 v5, 0x41f

    if-gt p0, v5, :cond_1fd9

    .line 119
    const/16 v2, 0x35

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_1fd9
    const/16 v5, 0x43c

    if-lt p0, v5, :cond_1fd

    const/16 v5, 0x43f

    if-gt p0, v5, :cond_1fd

    .line 119
    const/16 v2, 0x35

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_1fd
    const/16 v5, 0x3141

    if-ne p0, v5, :cond_205

    .line 119
    const/16 v2, 0x35

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 117
    .end local v2
    :cond_205
    const/16 v5, 0x62f      #5-from

    if-lt p0, v5, :cond_e

    const/16 v5, 0x632      #5-to

    if-gt p0, v5, :cond_e

    .line 119
    const/16 v2, 0x35       #5

    .restart local v2
    goto/16 :goto_10

    .line 117
    .end local v2
    :cond_e
    const/16 v5, 0x698      #5-from

    if-ne p0, v5, :cond_f

    .line 119
    const/16 v2, 0x35       #5

    .restart local v2
    goto/16 :goto_10

    .line 117
    .end local v2           #c1:C
    :cond_f
    const/16 v5, 0x5d9

    if-lt p0, v5, :cond_10

    const/16 v5, 0x5dc

    if-gt p0, v5, :cond_10

    .line 119
    const/16 v2, 0x35

    .restart local v2       #c1:C
    goto/16 :goto_10	
	
    .line 113
    .end local v2           #c1:C
    :cond_10
    const/16 v5, 0xd1

    if-lt p0, v5, :cond_211

    const/16 v5, 0xd8

    if-gt p0, v5, :cond_211

    .line 115
    const/16 v2, 0x36

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_211
    const/16 v5, 0xf1

    if-lt p0, v5, :cond_21d

    const/16 v5, 0xf8

    if-gt p0, v5, :cond_21d

    .line 115
    const/16 v2, 0x36

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_21d
    const/16 v5, 0x143

    if-lt p0, v5, :cond_229

    const/16 v5, 0x153

    if-gt p0, v5, :cond_229

    .line 115
    const/16 v2, 0x36

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_229
    const/16 v5, 0x19c

    if-lt p0, v5, :cond_235

    const/16 v5, 0x1a3

    if-gt p0, v5, :cond_235

    .line 115
    const/16 v2, 0x36

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_235
    const/16 v5, 0x38c

    if-ne p0, v5, :cond_23d

    .line 115
    const/16 v2, 0x36

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_23d
    const/16 v5, 0x39d

    if-lt p0, v5, :cond_249

    const/16 v5, 0x39f

    if-gt p0, v5, :cond_249

    .line 115
    const/16 v2, 0x36

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_249
    const/16 v5, 0x3bd

    if-lt p0, v5, :cond_255

    const/16 v5, 0x3bf

    if-gt p0, v5, :cond_255

    .line 115
    const/16 v2, 0x36

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_255
    const/16 v5, 0x3cc

    if-ne p0, v5, :cond_25d

    .line 115
    const/16 v2, 0x36

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_25d
    const/16 v5, 0x420

    if-lt p0, v5, :cond_2699

    const/16 v5, 0x423

    if-gt p0, v5, :cond_2699

    .line 115
    const/16 v2, 0x36

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_2699
    const/16 v5, 0x440

    if-lt p0, v5, :cond_269

    const/16 v5, 0x443

    if-gt p0, v5, :cond_269

    .line 115
    const/16 v2, 0x36

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_269
    const/16 v5, 0x1ecc

    if-lt p0, v5, :cond_275

    const/16 v5, 0x1ee3

    if-gt p0, v5, :cond_275

    .line 115
    const/16 v2, 0x36

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_275
    const/16 v5, 0x3142

    if-ne p0, v5, :cond_27d

    .line 115
    const/16 v2, 0x36

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_27d
    const/16 v5, 0x314d

    if-ne p0, v5, :cond_285

    .line 115
    const/16 v2, 0x36

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 113
    .end local v2
    :cond_285
    const/16 v5, 0x62c      #6-from

    if-lt p0, v5, :cond_11

    const/16 v5, 0x62e      #6-to

    if-gt p0, v5, :cond_11

    .line 115
    const/16 v2, 0x36       #6

    .restart local v2
    goto/16 :goto_10

    .line 113
    .end local v2
    :cond_11
    const/16 v5, 0x686      #6-from

    if-ne p0, v5, :cond_12

    .line 115
    const/16 v2, 0x36       #6

    .restart local v2
    goto/16 :goto_10

    .line 113
    .end local v2           #c1:C
    :cond_12
    const/16 v5, 0x5d6

    if-lt p0, v5, :cond_13

    const/16 v5, 0x5d8

    if-gt p0, v5, :cond_13

    .line 115
    const/16 v2, 0x36

    .restart local v2       #c1:C
    goto/16 :goto_10	
	
    .line 113
    .end local v2           #c1:C
    :cond_13
    const/16 v5, 0xdf

    if-ne p0, v5, :cond_28d

    .line 115
    const/16 v2, 0x37

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 133
    .end local v2           #c1:C
    :cond_28d
    const/16 v5, 0x154

    if-lt p0, v5, :cond_299

    const/16 v5, 0x161

    if-gt p0, v5, :cond_299

    .line 115
    const/16 v2, 0x37

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 133
    .end local v2           #c1:C
    :cond_299
    const/16 v5, 0x1a4

    if-lt p0, v5, :cond_2a5

    const/16 v5, 0x1aa

    if-gt p0, v5, :cond_2a5

    .line 115
    const/16 v2, 0x37

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 133
    .end local v2           #c1:C
    :cond_2a5
    const/16 v5, 0x3a0

    if-lt p0, v5, :cond_2b1

    const/16 v5, 0x3a3

    if-gt p0, v5, :cond_2b1

    .line 115
    const/16 v2, 0x37

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 133
    .end local v2           #c1:C
    :cond_2b1
    const/16 v5, 0x3c0

    if-lt p0, v5, :cond_2bd

    const/16 v5, 0x3c3

    if-gt p0, v5, :cond_2bd

    .line 115
    const/16 v2, 0x37

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 133
    .end local v2           #c1:C
    :cond_2bd
    const/16 v5, 0x424

    if-lt p0, v5, :cond_2c97

    const/16 v5, 0x427

    if-gt p0, v5, :cond_2c97

    .line 115
    const/16 v2, 0x37

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 133
    .end local v2           #c1:C
    :cond_2c97
    const/16 v5, 0x444

    if-lt p0, v5, :cond_2c9

    const/16 v5, 0x447

    if-gt p0, v5, :cond_2c9

    .line 115
    const/16 v2, 0x37

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 133
    .end local v2           #c1:C
    :cond_2c9
    const/16 v5, 0x3145

    if-ne p0, v5, :cond_2d1

    .line 115
    const/16 v2, 0x37

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 133
    .end local v2
    :cond_2d1
    const/16 v5, 0x646      #7-from

    if-lt p0, v5, :cond_14

    const/16 v5, 0x648      #7-to

    if-gt p0, v5, :cond_14

    .line 135
    const/16 v2, 0x37       #7

    .restart local v2
    goto/16 :goto_10

    .line 133
    .end local v2
    :cond_14
    const/16 v5, 0x6cc      #7-from

    if-ne p0, v5, :cond_15

    .line 135
    const/16 v2, 0x37       #7

    .restart local v2
    goto/16 :goto_10

    .line 133
    .end local v2
    :cond_15
    const/16 v5, 0x64a      #7-from

    if-ne p0, v5, :cond_16

    .line 135
    const/16 v2, 0x37       #7

    .restart local v2
    goto/16 :goto_10

    .line 133
    .end local v2
    :cond_16
    const/16 v5, 0x624      #7-from

    if-ne p0, v5, :cond_17

    .line 135
    const/16 v2, 0x37       #7

    .restart local v2
    goto/16 :goto_10

    .line 133
    .end local v2
    :cond_17
    const/16 v5, 0x626      #7-from

    if-ne p0, v5, :cond_18

    .line 135
    const/16 v2, 0x37       #7

    .restart local v2
    goto/16 :goto_10
	
    .line 133
    .end local v2           #c1:C
    :cond_18
    const/16 v5, 0x5e8

    if-lt p0, v5, :cond_19

    const/16 v5, 0x5ea

    if-gt p0, v5, :cond_19

    .line 135
    const/16 v2, 0x37

    .restart local v2       #c1:C
    goto/16 :goto_10	

    .line 133
    .end local v2           #c1:C
    :cond_19
    const/16 v5, 0xd9

    if-lt p0, v5, :cond_2dd

    const/16 v5, 0xdc

    if-gt p0, v5, :cond_2dd

    .line 135
    const/16 v2, 0x38

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 129
    .end local v2           #c1:C
    :cond_2dd
    const/16 v5, 0xf9

    if-lt p0, v5, :cond_2e9

    const/16 v5, 0xfc

    if-gt p0, v5, :cond_2e9

    .line 131
    const/16 v2, 0x38

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_2e9
    const/16 v5, 0x162

    if-lt p0, v5, :cond_2f5

    const/16 v5, 0x173

    if-gt p0, v5, :cond_2f5

    .line 131
    const/16 v2, 0x38

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_2f5
    const/16 v5, 0x1ab

    if-lt p0, v5, :cond_301

    const/16 v5, 0x1b2

    if-gt p0, v5, :cond_301

    .line 131
    const/16 v2, 0x38

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_301
    const/16 v5, 0x1d3

    if-lt p0, v5, :cond_30d

    const/16 v5, 0x1dc

    if-gt p0, v5, :cond_30d

    .line 131
    const/16 v2, 0x38

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_30d
    const/16 v5, 0x3a4

    if-lt p0, v5, :cond_319

    const/16 v5, 0x3a6

    if-gt p0, v5, :cond_319

    .line 131
    const/16 v2, 0x38

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_319
    const/16 v5, 0x3c4

    if-lt p0, v5, :cond_325

    const/16 v5, 0x3c6

    if-gt p0, v5, :cond_325

    .line 131
    const/16 v2, 0x38

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_325
    const/16 v5, 0x3cb

    if-ne p0, v5, :cond_32d

    .line 131
    const/16 v2, 0x38

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_32d
    const/16 v5, 0x428

    if-lt p0, v5, :cond_3393

    const/16 v5, 0x42b

    if-gt p0, v5, :cond_3393

    .line 131
    const/16 v2, 0x38

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_3393
    const/16 v5, 0x448

    if-lt p0, v5, :cond_339

    const/16 v5, 0x44b

    if-gt p0, v5, :cond_339

    .line 131
    const/16 v2, 0x38

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_339
    const/16 v5, 0x1ee4

    if-lt p0, v5, :cond_345

    const/16 v5, 0x1ef1

    if-gt p0, v5, :cond_345

    .line 131
    const/16 v2, 0x38

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_345
    const/16 v5, 0x3147

    if-ne p0, v5, :cond_34d

    .line 131
    const/16 v2, 0x38

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 129
    .end local v2
    :cond_34d
    const/16 v5, 0x641      #8-from

    if-lt p0, v5, :cond_1a

    const/16 v5, 0x645      #8-to

    if-gt p0, v5, :cond_1a

    .line 131
    const/16 v2, 0x38       #8

    .restart local v2
    goto/16 :goto_10

    .line 129
    .end local v2
    :cond_1a
    const/16 v5, 0x6a9      #8-from

    if-ne p0, v5, :cond_1b

    .line 131
    const/16 v2, 0x38       #8

    .restart local v2
    goto/16 :goto_10

    .line 129
    .end local v2
    :cond_1b
    const/16 v5, 0x6af      #8-from

    if-ne p0, v5, :cond_1c

    .line 131
    const/16 v2, 0x38       #8

    .restart local v2
    goto/16 :goto_10
	
    .line 129
    .end local v2           #c1:C
    :cond_1c
    const/16 v5, 0x5e5

    if-lt p0, v5, :cond_1d

    const/16 v5, 0x5e7

    if-gt p0, v5, :cond_1d

    .line 131
    const/16 v2, 0x38

    .restart local v2       #c1:C
    goto/16 :goto_10	

    .line 138
    .end local v2           #c1:C
    :cond_1d
    const/16 v5, 0xdd

    if-ne p0, v5, :cond_355

    .line 131
    const/16 v2, 0x39

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_355
    const/16 v5, 0xfd

    if-ne p0, v5, :cond_35d

    .line 131
    const/16 v2, 0x39

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_35d
    const/16 v5, 0x174

    if-lt p0, v5, :cond_369

    const/16 v5, 0x17e

    if-gt p0, v5, :cond_369

    .line 131
    const/16 v2, 0x39

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    :cond_369
    const/16 v5, 0x1b3

    if-lt p0, v5, :cond_375

    const/16 v5, 0x1bf

    if-gt p0, v5, :cond_375

    .line 131
    const/16 v2, 0x39

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    .end local v2           #c1:C
    :cond_375
    const/16 v5, 0x38f

    if-ne p0, v5, :cond_37d

    .line 131
    const/16 v2, 0x39

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_37d
    const/16 v5, 0x3a7

    if-lt p0, v5, :cond_389

    const/16 v5, 0x3a9

    if-gt p0, v5, :cond_389

    .line 131
    const/16 v2, 0x39

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_389
    const/16 v5, 0x3c7

    if-lt p0, v5, :cond_395

    const/16 v5, 0x3c9

    if-gt p0, v5, :cond_395

    .line 131
    const/16 v2, 0x39

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_395
    const/16 v5, 0x3ce

    if-ne p0, v5, :cond_39d

    .line 131
    const/16 v2, 0x39

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_39d
    const/16 v5, 0x42c

    if-lt p0, v5, :cond_3a9a

    const/16 v5, 0x42f

    if-gt p0, v5, :cond_3a9a

    .line 131
    const/16 v2, 0x39

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_3a9a
    const/16 v5, 0x44c

    if-lt p0, v5, :cond_3a9

    const/16 v5, 0x44f

    if-gt p0, v5, :cond_3a9

    .line 131
    const/16 v2, 0x39

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_3a9
    const/16 v5, 0x1ef2

    if-lt p0, v5, :cond_3b5

    const/16 v5, 0x1ef9

    if-gt p0, v5, :cond_3b5

    .line 131
    const/16 v2, 0x39

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_3b5
    const/16 v5, 0x3148

    if-ne p0, v5, :cond_3bd

    .line 131
    const/16 v2, 0x39

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_3bd
    const/16 v5, 0x314a

    if-ne p0, v5, :cond_3c5

    .line 131
    const/16 v2, 0x39

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 125
    .end local v2 
    :cond_3c5
    const/16 v5, 0x637      #9-from

    if-lt p0, v5, :cond_1e

    const/16 v5, 0x63a      #9-to

    if-gt p0, v5, :cond_1e

    .line 127
    const/16 v2, 0x39       #9

    .restart local v2
    goto/16 :goto_10
	
    .line 125
    .end local v2           #c1:C
    :cond_1e
    const/16 v5, 0x5e1

    if-lt p0, v5, :cond_1f

    const/16 v5, 0x5e4

    if-gt p0, v5, :cond_1f

    .line 127
    const/16 v2, 0x39

    .restart local v2       #c1:C
    goto/16 :goto_10	

    .line 138
    .end local v2           #c1:C
    :cond_1f
    const/16 v5, 0x314e

    if-ne p0, v5, :cond_3cd

    .line 131
    const/16 v2, 0x30

    .restart local v2       #c1:C
    goto/16 :goto_10

    .line 138
    .end local v2           #c1:C
    :cond_3cd
    const/4 v2, 0x0

    .restart local v2       #c1:C
    goto/16 :goto_10
.end method

.method public static formatCharToT9(Ljava/lang/String;)Ljava/lang/String;
    .registers 6
    .parameter "s"

    .prologue
    .line 391
    invoke-static {p0}, Landroid/text/TextUtils;->isEmpty(Ljava/lang/CharSequence;)Z

    move-result v3

    if-eqz v3, :cond_8

    .line 392
    const/4 v3, 0x0

    .line 409
    :goto_7
    return-object v3

    .line 395
    :cond_8
    new-instance v0, Ljava/lang/StringBuilder;

    invoke-virtual {p0}, Ljava/lang/String;->length()I

    move-result v3

    invoke-direct {v0, v3}, Ljava/lang/StringBuilder;-><init>(I)V

    .line 396
    .local v0, builder:Ljava/lang/StringBuilder;
    const/4 v2, 0x0

    .local v2, i:I
    :goto_12
    invoke-virtual {p0}, Ljava/lang/String;->length()I

    move-result v3

    if-ge v2, v3, :cond_4f

    .line 397
    invoke-virtual {p0, v2}, Ljava/lang/String;->charAt(I)C

    move-result v1

    .line 398
    .local v1, c:I
    const/16 v3, 0x41

    if-lt v1, v3, :cond_30

    const/16 v3, 0x5a

    if-gt v1, v3, :cond_30

    .line 399
    sget-object v3, Lmiui/util/HanziToPinyin;->sT9Map:[C

    add-int/lit8 v4, v1, -0x41

    aget-char v3, v3, v4

    invoke-virtual {v0, v3}, Ljava/lang/StringBuilder;->append(C)Ljava/lang/StringBuilder;

    .line 396
    :cond_2d
    :goto_2d
    add-int/lit8 v2, v2, 0x1

    goto :goto_12

    .line 400
    :cond_30
    const/16 v3, 0x61

    if-lt v1, v3, :cond_42

    const/16 v3, 0x7a

    if-gt v1, v3, :cond_42

    .line 401
    sget-object v3, Lmiui/util/HanziToPinyin;->sT9Map:[C

    add-int/lit8 v4, v1, -0x61

    aget-char v3, v3, v4

    invoke-virtual {v0, v3}, Ljava/lang/StringBuilder;->append(C)Ljava/lang/StringBuilder;

    goto :goto_2d

    .line 402
    :cond_42
    const/16 v3, 0x30

    if-lt v1, v3, :cond_2d

    const/16 v3, 0x39

    if-gt v1, v3, :cond_2d

    .line 403
    int-to-char v3, v1

    invoke-virtual {v0, v3}, Ljava/lang/StringBuilder;->append(C)Ljava/lang/StringBuilder;

    goto :goto_2d

    .line 409
    .end local v1           #c:I
    :cond_4f
    invoke-virtual {v0}, Ljava/lang/StringBuilder;->toString()Ljava/lang/String;

    move-result-object v3

    goto :goto_7
.end method

.method public static getInstance()Lmiui/util/HanziToPinyin;
    .registers 5

    .prologue
    .line 206
    const-class v3, Lmiui/util/HanziToPinyin;

    monitor-enter v3

    .line 207
    :try_start_3
    sget-object v2, Lmiui/util/HanziToPinyin;->sInstance:Lmiui/util/HanziToPinyin;

    if-eqz v2, :cond_b

    .line 208
    sget-object v2, Lmiui/util/HanziToPinyin;->sInstance:Lmiui/util/HanziToPinyin;

    monitor-exit v3

    .line 220
    .local v0, i:I
    .local v1, locale:[Ljava/util/Locale;
    :goto_a
    return-object v2

    .line 211
    .end local v0           #i:I
    .end local v1           #locale:[Ljava/util/Locale;
    :cond_b
    invoke-static {}, Ljava/text/Collator;->getAvailableLocales()[Ljava/util/Locale;

    move-result-object v1

    .line 212
    .restart local v1       #locale:[Ljava/util/Locale;
    const/4 v0, 0x0

    .restart local v0       #i:I
    :goto_10
    array-length v2, v1

    if-ge v0, v2, :cond_2f

    .line 213
    aget-object v2, v1, v0

    sget-object v4, Ljava/util/Locale;->CHINA:Ljava/util/Locale;

    invoke-virtual {v2, v4}, Ljava/util/Locale;->equals(Ljava/lang/Object;)Z

    move-result v2

    if-eqz v2, :cond_2c

    .line 214
    new-instance v2, Lmiui/util/HanziToPinyin;

    const/4 v4, 0x1

    invoke-direct {v2, v4}, Lmiui/util/HanziToPinyin;-><init>(Z)V

    sput-object v2, Lmiui/util/HanziToPinyin;->sInstance:Lmiui/util/HanziToPinyin;

    .line 215
    sget-object v2, Lmiui/util/HanziToPinyin;->sInstance:Lmiui/util/HanziToPinyin;

    monitor-exit v3

    goto :goto_a

    .line 221
    :catchall_29
    move-exception v2

    monitor-exit v3
    :try_end_2b
    .catchall {:try_start_3 .. :try_end_2b} :catchall_29

    throw v2

    .line 212
    :cond_2c
    add-int/lit8 v0, v0, 0x1

    goto :goto_10

    .line 218
    :cond_2f
    :try_start_2f
    const-string v2, "HanziToPinyin"

    const-string v4, "There is no Chinese collator, HanziToPinyin is disabled"

    invoke-static {v2, v4}, Landroid/util/Log;->w(Ljava/lang/String;Ljava/lang/String;)I

    .line 219
    new-instance v2, Lmiui/util/HanziToPinyin;

    const/4 v4, 0x0

    invoke-direct {v2, v4}, Lmiui/util/HanziToPinyin;-><init>(Z)V

    sput-object v2, Lmiui/util/HanziToPinyin;->sInstance:Lmiui/util/HanziToPinyin;

    .line 220
    sget-object v2, Lmiui/util/HanziToPinyin;->sInstance:Lmiui/util/HanziToPinyin;

    monitor-exit v3
    :try_end_41
    .catchall {:try_start_2f .. :try_end_41} :catchall_29

    goto :goto_a
.end method

.method private getPolyPhoneLastNameTokens(Ljava/lang/String;)Ljava/util/ArrayList;
    .registers 13
    .parameter "name"
    .annotation system Ldalvik/annotation/Signature;
        value = {
            "(",
            "Ljava/lang/String;",
            ")",
            "Ljava/util/ArrayList",
            "<",
            "Lmiui/util/HanziToPinyin$Token;",
            ">;"
        }
    .end annotation

    .prologue
    const/4 v7, 0x0

    const/4 v10, 0x0

    const/4 v9, 0x2

    .line 226
    invoke-static {p1}, Landroid/text/TextUtils;->isEmpty(Ljava/lang/CharSequence;)Z

    move-result v8

    if-eqz v8, :cond_b

    move-object v6, v7

    .line 260
    :cond_a
    :goto_a
    return-object v6

    .line 230
    :cond_b
    new-instance v6, Ljava/util/ArrayList;

    invoke-direct {v6}, Ljava/util/ArrayList;-><init>()V

    .line 233
    .local v6, tokens:Ljava/util/ArrayList;,"Ljava/util/ArrayList<Lmiui/util/HanziToPinyin$Token;>;"
    invoke-virtual {p1}, Ljava/lang/String;->length()I

    move-result v8

    if-lt v8, v9, :cond_43

    .line 234
    invoke-virtual {p1, v10, v9}, Ljava/lang/String;->substring(II)Ljava/lang/String;

    move-result-object v0

    .line 235
    .local v0, hyphenatedName:Ljava/lang/String;
    sget-object v8, Lmiui/util/HanziToPinyin;->sHyphenatedNamePolyPhoneMap:Ljava/util/HashMap;

    invoke-virtual {v8, v0}, Ljava/util/HashMap;->get(Ljava/lang/Object;)Ljava/lang/Object;

    move-result-object v4

    check-cast v4, [Ljava/lang/String;

    .line 236
    .local v4, polyPhones:[Ljava/lang/String;
    if-eqz v4, :cond_43

    .line 237
    const/4 v1, 0x0

    .local v1, i:I
    :goto_25
    array-length v7, v4

    if-ge v1, v7, :cond_a

    .line 238
    new-instance v5, Lmiui/util/HanziToPinyin$Token;

    invoke-direct {v5}, Lmiui/util/HanziToPinyin$Token;-><init>()V

    .line 239
    .local v5, token:Lmiui/util/HanziToPinyin$Token;
    iput v9, v5, Lmiui/util/HanziToPinyin$Token;->type:I

    .line 240
    invoke-virtual {v0, v1}, Ljava/lang/String;->charAt(I)C

    move-result v7

    invoke-static {v7}, Ljava/lang/String;->valueOf(C)Ljava/lang/String;

    move-result-object v7

    iput-object v7, v5, Lmiui/util/HanziToPinyin$Token;->source:Ljava/lang/String;

    .line 241
    aget-object v7, v4, v1

    iput-object v7, v5, Lmiui/util/HanziToPinyin$Token;->target:Ljava/lang/String;

    .line 242
    invoke-virtual {v6, v5}, Ljava/util/ArrayList;->add(Ljava/lang/Object;)Z

    .line 237
    add-int/lit8 v1, v1, 0x1

    goto :goto_25

    .line 249
    .end local v0           #hyphenatedName:Ljava/lang/String;
    .end local v1           #i:I
    .end local v4           #polyPhones:[Ljava/lang/String;
    .end local v5           #token:Lmiui/util/HanziToPinyin$Token;
    :cond_43
    invoke-virtual {p1, v10}, Ljava/lang/String;->charAt(I)C

    move-result v8

    invoke-static {v8}, Ljava/lang/Character;->valueOf(C)Ljava/lang/Character;

    move-result-object v2

    .line 250
    .local v2, lastName:Ljava/lang/Character;
    sget-object v8, Lmiui/util/HanziToPinyin;->sLastNamePolyPhoneMap:Ljava/util/HashMap;

    invoke-virtual {v8, v2}, Ljava/util/HashMap;->get(Ljava/lang/Object;)Ljava/lang/Object;

    move-result-object v3

    check-cast v3, Ljava/lang/String;

    .line 251
    .local v3, polyPhone:Ljava/lang/String;
    if-eqz v3, :cond_68

    .line 252
    new-instance v5, Lmiui/util/HanziToPinyin$Token;

    invoke-direct {v5}, Lmiui/util/HanziToPinyin$Token;-><init>()V

    .line 253
    .restart local v5       #token:Lmiui/util/HanziToPinyin$Token;
    iput v9, v5, Lmiui/util/HanziToPinyin$Token;->type:I

    .line 254
    invoke-virtual {v2}, Ljava/lang/Character;->toString()Ljava/lang/String;

    move-result-object v7

    iput-object v7, v5, Lmiui/util/HanziToPinyin$Token;->source:Ljava/lang/String;

    .line 255
    iput-object v3, v5, Lmiui/util/HanziToPinyin$Token;->target:Ljava/lang/String;

    .line 256
    invoke-virtual {v6, v5}, Ljava/util/ArrayList;->add(Ljava/lang/Object;)Z

    goto :goto_a

    .end local v5           #token:Lmiui/util/HanziToPinyin$Token;
    :cond_68
    move-object v6, v7

    .line 260
    goto :goto_a
.end method


# virtual methods
.method public get(Ljava/lang/String;)Ljava/util/ArrayList;
    .registers 3
    .parameter "input"
    .annotation system Ldalvik/annotation/Signature;
        value = {
            "(",
            "Ljava/lang/String;",
            ")",
            "Ljava/util/ArrayList",
            "<",
            "Lmiui/util/HanziToPinyin$Token;",
            ">;"
        }
    .end annotation

    .prologue
    const/4 v0, 0x1

    .line 270
    invoke-virtual {p0, p1, v0, v0}, Lmiui/util/HanziToPinyin;->get(Ljava/lang/String;ZZ)Ljava/util/ArrayList;

    move-result-object v0

    return-object v0
.end method

.method public get(Ljava/lang/String;ZZ)Ljava/util/ArrayList;
    .registers 17
    .parameter "input"
    .parameter "filterInvalidChar"
    .parameter "ignoreLastName"
    .annotation system Ldalvik/annotation/Signature;
        value = {
            "(",
            "Ljava/lang/String;",
            "ZZ)",
            "Ljava/util/ArrayList",
            "<",
            "Lmiui/util/HanziToPinyin$Token;",
            ">;"
        }
    .end annotation

    .prologue
    .line 285
    new-instance v10, Ljava/util/ArrayList;

    invoke-direct {v10}, Ljava/util/ArrayList;-><init>()V

    .line 286
    .local v10, tokens:Ljava/util/ArrayList;,"Ljava/util/ArrayList<Lmiui/util/HanziToPinyin$Token;>;"
    iget-boolean v11, p0, Lmiui/util/HanziToPinyin;->mHasChinaCollator:Z

    if-eqz v11, :cond_f

    invoke-static {p1}, Landroid/text/TextUtils;->isEmpty(Ljava/lang/CharSequence;)Z

    move-result v11

    if-eqz v11, :cond_10

    .line 370
    :cond_f
    :goto_f
    return-object v10

    .line 291
    :cond_10
    const/4 v7, 0x0

    .line 292
    .local v7, startIndex:I
    if-nez p3, :cond_26

    .line 293
    invoke-direct {p0, p1}, Lmiui/util/HanziToPinyin;->getPolyPhoneLastNameTokens(Ljava/lang/String;)Ljava/util/ArrayList;

    move-result-object v3

    .line 294
    .local v3, polyPhoneLastNameTokens:Ljava/util/ArrayList;,"Ljava/util/ArrayList<Lmiui/util/HanziToPinyin$Token;>;"
    if-eqz v3, :cond_26

    invoke-virtual {v3}, Ljava/util/ArrayList;->size()I

    move-result v11

    if-lez v11, :cond_26

    .line 295
    invoke-virtual {v10, v3}, Ljava/util/ArrayList;->addAll(Ljava/util/Collection;)Z

    .line 296
    invoke-virtual {v3}, Ljava/util/ArrayList;->size()I

    move-result v7

    .line 300
    .end local v3           #polyPhoneLastNameTokens:Ljava/util/ArrayList;,"Ljava/util/ArrayList<Lmiui/util/HanziToPinyin$Token;>;"
    :cond_26
    invoke-virtual {p1}, Ljava/lang/String;->length()I

    move-result v2

    .line 301
    .local v2, inputLength:I
    new-instance v5, Ljava/lang/StringBuilder;

    invoke-direct {v5}, Ljava/lang/StringBuilder;-><init>()V

    .line 302
    .local v5, sb:Ljava/lang/StringBuilder;
    const/4 v9, 0x1

    .line 307
    .local v9, tokenType:I
    move v1, v7

    .local v1, i:I
    :goto_31
    if-ge v1, v2, :cond_f5

    .line 308
    invoke-virtual {p1, v1}, Ljava/lang/String;->charAt(I)C

    move-result v0

    .line 309
    .local v0, character:C
    const/16 v11, 0x20

    if-ne v0, v11, :cond_59

    .line 310
    invoke-virtual {v5}, Ljava/lang/StringBuilder;->length()I

    move-result v11

    if-lez v11, :cond_44

    .line 311
    invoke-direct {p0, v5, v10, v9}, Lmiui/util/HanziToPinyin;->addToken(Ljava/lang/StringBuilder;Ljava/util/ArrayList;I)V

    .line 313
    :cond_44
    if-nez p2, :cond_55

    .line 314
    const/16 v11, 0x20

    invoke-static {v11}, Ljava/lang/String;->valueOf(C)Ljava/lang/String;

    move-result-object v6

    .line 315
    .local v6, separator:Ljava/lang/String;
    new-instance v11, Lmiui/util/HanziToPinyin$Token;

    const/4 v12, 0x3

    invoke-direct {v11, v12, v6, v6}, Lmiui/util/HanziToPinyin$Token;-><init>(ILjava/lang/String;Ljava/lang/String;)V

    invoke-virtual {v10, v11}, Ljava/util/ArrayList;->add(Ljava/lang/Object;)Z

    .line 317
    .end local v6           #separator:Ljava/lang/String;
    :cond_55
    const/4 v9, 0x3

    .line 307
    :goto_56
    add-int/lit8 v1, v1, 0x1

    goto :goto_31

    .line 318
    :cond_59
    const/16 v11, 0x100

    if-ge v0, v11, :cond_6e

    .line 319
    const/4 v11, 0x1

    if-eq v9, v11, :cond_69

    invoke-virtual {v5}, Ljava/lang/StringBuilder;->length()I

    move-result v11

    if-lez v11, :cond_69

    .line 320
    invoke-direct {p0, v5, v10, v9}, Lmiui/util/HanziToPinyin;->addToken(Ljava/lang/StringBuilder;Ljava/util/ArrayList;I)V

    .line 322
    :cond_69
    const/4 v9, 0x1

    .line 323
    invoke-virtual {v5, v0}, Ljava/lang/StringBuilder;->append(C)Ljava/lang/StringBuilder;

    goto :goto_56

    .line 324
    :cond_6e
    const/16 v11, 0x3007

    if-ne v0, v11, :cond_8c

    .line 325
    new-instance v8, Lmiui/util/HanziToPinyin$Token;

    invoke-direct {v8}, Lmiui/util/HanziToPinyin$Token;-><init>()V

    .line 326
    .local v8, token:Lmiui/util/HanziToPinyin$Token;
    const/4 v11, 0x2

    iput v11, v8, Lmiui/util/HanziToPinyin$Token;->type:I

    .line 327
    const-string v11, "ling"

    iput-object v11, v8, Lmiui/util/HanziToPinyin$Token;->target:Ljava/lang/String;

    .line 328
    invoke-virtual {v5}, Ljava/lang/StringBuilder;->length()I

    move-result v11

    if-lez v11, :cond_87

    .line 329
    invoke-direct {p0, v5, v10, v9}, Lmiui/util/HanziToPinyin;->addToken(Ljava/lang/StringBuilder;Ljava/util/ArrayList;I)V

    .line 331
    :cond_87
    invoke-virtual {v10, v8}, Ljava/util/ArrayList;->add(Ljava/lang/Object;)Z

    .line 332
    const/4 v9, 0x2

    .line 333
    goto :goto_56

    .end local v8           #token:Lmiui/util/HanziToPinyin$Token;
    :cond_8c
    const/16 v11, 0x4e00

    if-lt v0, v11, :cond_e3

    const v11, 0x9fa5

    if-gt v0, v11, :cond_e3

    .line 334
    invoke-static {}, Lmiui/util/HanziToPinyinHelper;->getIntance()Lmiui/util/HanziToPinyinHelper;

    move-result-object v11

    invoke-virtual {v11, v0}, Lmiui/util/HanziToPinyinHelper;->getPinyinString(C)[Ljava/lang/String;

    move-result-object v4

    .line 335
    .local v4, polyPhones:[Ljava/lang/String;
    new-instance v8, Lmiui/util/HanziToPinyin$Token;

    invoke-direct {v8}, Lmiui/util/HanziToPinyin$Token;-><init>()V

    .line 336
    .restart local v8       #token:Lmiui/util/HanziToPinyin$Token;
    if-nez v4, :cond_c0

    .line 337
    const/4 v11, 0x3

    iput v11, v8, Lmiui/util/HanziToPinyin$Token;->type:I

    .line 338
    invoke-static {v0}, Ljava/lang/Character;->toString(C)Ljava/lang/String;

    move-result-object v11

    iput-object v11, v8, Lmiui/util/HanziToPinyin$Token;->target:Ljava/lang/String;

    .line 346
    :cond_ad
    :goto_ad
    iget v11, v8, Lmiui/util/HanziToPinyin$Token;->type:I

    const/4 v12, 0x2

    if-ne v11, v12, :cond_cf

    .line 347
    invoke-virtual {v5}, Ljava/lang/StringBuilder;->length()I

    move-result v11

    if-lez v11, :cond_bb

    .line 348
    invoke-direct {p0, v5, v10, v9}, Lmiui/util/HanziToPinyin;->addToken(Ljava/lang/StringBuilder;Ljava/util/ArrayList;I)V

    .line 350
    :cond_bb
    invoke-virtual {v10, v8}, Ljava/util/ArrayList;->add(Ljava/lang/Object;)Z

    .line 351
    const/4 v9, 0x2

    goto :goto_56

    .line 340
    :cond_c0
    const/4 v11, 0x2

    iput v11, v8, Lmiui/util/HanziToPinyin$Token;->type:I

    .line 341
    const/4 v11, 0x0

    aget-object v11, v4, v11

    iput-object v11, v8, Lmiui/util/HanziToPinyin$Token;->target:Ljava/lang/String;

    .line 342
    array-length v11, v4

    const/4 v12, 0x1

    if-le v11, v12, :cond_ad

    .line 343
    iput-object v4, v8, Lmiui/util/HanziToPinyin$Token;->polyPhones:[Ljava/lang/String;

    goto :goto_ad

    .line 353
    :cond_cf
    iget v11, v8, Lmiui/util/HanziToPinyin$Token;->type:I

    if-eq v9, v11, :cond_dc

    invoke-virtual {v5}, Ljava/lang/StringBuilder;->length()I

    move-result v11

    if-lez v11, :cond_dc

    .line 354
    invoke-direct {p0, v5, v10, v9}, Lmiui/util/HanziToPinyin;->addToken(Ljava/lang/StringBuilder;Ljava/util/ArrayList;I)V

    .line 356
    :cond_dc
    iget v9, v8, Lmiui/util/HanziToPinyin$Token;->type:I

    .line 357
    invoke-virtual {v5, v0}, Ljava/lang/StringBuilder;->append(C)Ljava/lang/StringBuilder;

    goto/16 :goto_56

    .line 360
    .end local v4           #polyPhones:[Ljava/lang/String;
    .end local v8           #token:Lmiui/util/HanziToPinyin$Token;
    :cond_e3
    const/4 v11, 0x3

    if-eq v9, v11, :cond_ef

    invoke-virtual {v5}, Ljava/lang/StringBuilder;->length()I

    move-result v11

    if-lez v11, :cond_ef

    .line 361
    invoke-direct {p0, v5, v10, v9}, Lmiui/util/HanziToPinyin;->addToken(Ljava/lang/StringBuilder;Ljava/util/ArrayList;I)V

    .line 363
    :cond_ef
    const/4 v9, 0x3

    .line 364
    invoke-virtual {v5, v0}, Ljava/lang/StringBuilder;->append(C)Ljava/lang/StringBuilder;

    goto/16 :goto_56

    .line 367
    .end local v0           #character:C
    :cond_f5
    invoke-virtual {v5}, Ljava/lang/StringBuilder;->length()I

    move-result v11

    if-lez v11, :cond_f

    .line 368
    invoke-direct {p0, v5, v10, v9}, Lmiui/util/HanziToPinyin;->addToken(Ljava/lang/StringBuilder;Ljava/util/ArrayList;I)V

    goto/16 :goto_f
.end method