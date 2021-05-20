<!DOCTYPE html>
<html lang="ja" dir="ltr">
<head>
<title> [MKW] Yamaguchi Mogi Stats</title>
</head>
<body>
    
    <style>
        table {
            border-collapse: collapse;
        }
        th {
            border: solid 1px #666666;
            color: #000000;
            background-color: #FFFFFF;
        }
        td {
            border: solid 1px #666666;
            color: #000000;
            background-color: #ffffff;
        }
        thead th {
            background-color: #C3E9F3;
        }
        </style>


    <section class="container">
        <script type="text/javascript">
            (function(document) {
  'use strict';

  var LightTableFilter = (function(Arr) {

    var _input;

    function _onInputEvent(e) {
      _input = e.target;
      var tables = document.getElementsByClassName(_input.getAttribute('data-table'));
      Arr.forEach.call(tables, function(table) {
        Arr.forEach.call(table.tBodies, function(tbody) {
          Arr.forEach.call(tbody.rows, _filter);
        });
      });
    }

    function _filter(row) {
      var text = row.textContent.toLowerCase(), val = _input.value.toLowerCase();
      row.style.display = text.indexOf(val) === -1 ? 'none' : 'table-row';
    }

    return {
      init: function() {
        var inputs = document.getElementsByClassName('light-table-filter');
        Arr.forEach.call(inputs, function(input) {
          input.oninput = _onInputEvent;
        });
      }
    };
  })(Array.prototype);

  document.addEventListener('readystatechange', function() {
    if (document.readyState === 'complete') {
      LightTableFilter.init();
    }
  });

})(document);
            console.log("JavaScriptを実行しています");
          </script>

     <input type="search" class="light-table-filter" data-table="order-table" placeholder="検索" />
        <table class="order-table">
            <thead>
                <tr>
                    <th>
                        Date
                    </th>
                    <th>
                        Format
                    </th>
                    <th>
                        Overview
                    </th>
                    <th>
                        Participants
                    </th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <th>
                        2020/10/3
                    </th>
                    <td>
                        1
                    </td>
                    <td>
                        First Mogi
                    </td>
                    <td>
                        Yamaguchi,Nobu,Heggu,Goreinu,Soba,once,Kocchi,Vasac
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/10/11
                    </th>
                    <td>
                        3
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Soba,Fiona,Hina,Nobu,Kocchi,Hinako,Bawp,Heggu,Hosokaw,(?),(?)
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/10/31
                    </th>
                    <td>
                        2
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Nobu,Tank,Hosokawa,Heggu,Dongira,Soba,Remi,Emperor,Vasac,Me3,Miyabi
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/11/8
                    </th>
                    <td>
                        4
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Soba,Remi,Goreinu,Finite,(?),(?)(?),(?),(?),(?),(?)
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/11/21
                    </th>
                    <td>
                        2
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Goreinu,Lugius,Mapu,Fiona,Hina,Dongira,Tarozaemon,Soba,Rc,Luis Hinako
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/11/21
                    </th>
                    <td>
                        2
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Goreinu,Asuna,marunasu,Uerin,Donaldo,Michael,Fiona,Hina,Sumiredo,Dorasu,Osusume
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/11/23
                    </th>
                    <td>
                        3
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Nathan,Jupiter,Hinako,Totori,Donaldo,Rigel(Milano),Kuro,Eimii,Vasac,Remi,Fiona
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/11/28
                    </th>
                    <td>
                        3
                    </td>
                    <td>
                        Wrong Settings
                    </td>
                    <td>
                        Yamaguchi,Soba,Remi,Hina,Uerin,Toku,Charichan,Nobu,Aku,Jonny,(?),(?)
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/2
                    </th>
                    <td>
                        2
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Negima,Michael,Miya,Amphas,Colt,Ryoko,Eimii,Kocchi,404,Vase,(?)
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/5
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Deco,Rigel,Uerin,Lion,Negima,Remi,Dorasu,Miya,Engelberg,Kotoran,Sigure
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/5
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Serufu,Uerin,Minato,Soba,Nyoni,Atama,Jackk,Miya,Sigure,Hinako,Draggy
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/6
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Babe,Reo,Uerin,Tank,Totori,Toku,Hina,Zeta,Tatsuya,Sabo,Yorunagi
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/9
                    </th>
                    <td>
                        3
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Uerin,Toku,Hina,Asuna,Sumiredo,Dorasu,Soba,Remi,Finite,(?),(?)
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/10
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Rc,Uerin,Yasuyoshi,Finite,Fiona,Dongira,Spica,Hina,Miya,Ammo,Sutapa
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/11
                    </th>
                    <td>
                        4
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Sutapa,Koua,Jackk,yuuki,Michael,Miya,Rc,Vanillaice,Kapera,Fiona,Toku
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/11
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Ayane,Kapera,404,Jackk,Toku,Goreinu,Rockk,Fiona,Koua,Rigel,Yuuki
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/11
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        First Draft 6v6
                    </td>
                    <td>
                        Yamaguchi,Mike,Finite,marunasu,EZ,Negima,YoshiKZ,JEX,Bobchan,Totori,Rc,Tatsuya
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/12
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Satopy,Eimii,Yorunagi,Wadahage,Yuuki,marunasu,Milano,Uerin,Kapera,Negima,Toku
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/12
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Rein,Soba,Miya,Koua,Donaldo,Milano,Uerin,Renzi,Yorunagi,Ammo,Dorasu
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/12
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,404,Maru,Negima,Mapu,Minato,Dorasu,Tank,Sabo,Ayane,Loser,Reo
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/13
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Kotoran,Jackk,Asuna,oga,osusume,Hina,Toku,Tank,Death Spear,Negima,Reo
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/13
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        Close Difference
                    </td>
                    <td>
                        Yamaguchi,Az,Yuni,Potato,Milano,Donaldo,Spica,Goreinu,Ammo,Mapu,Minato,Negima
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/13
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Yuni,Babe,Kapera,Ammo,Donaldo,Satopy,Miya,Totori,Saber,Trace,Pondy
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/13
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,KouBG,Maru,Sukay,snk,Deco,Ayane,Kocchi,Fuku,Asuna,Kapera,Yasuo
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/13
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Donaldo,Spica,Dorasu,Babe,Uerin,Koua,Yasuyoshi,Maru,Shun,Asuna,Michael
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/14
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        Jonny
                    </td>
                    <td>
                        Yamaguchi,Pondy,Sigure,Charichan,Spica,Toku,Kapera,Uerin,Fuku,Fiona,Jonny,Hina
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/14
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Sabo,Bobchan,Pondy,Peach,Jonny,Donaldo,Hiduke,Totori,Fuku,Tank,(?)
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/15
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,YoshiKZ,Michael,oga,EZ,Ayane,Koua,Sabo,Satopy,Tank,Bobchan,gmchan
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/16
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Nuno,Michael,Toku,Rigel,Yuuki,Kocchi,Akuril,Fiona,Spica,Jonny,Miya
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/16
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Ayane,EZ,YoshiKZ,Kapera,Rigel,Yuuki,Fiona,Donaldo,Uerin,Jackk,(?)
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/16
                    </th>
                    <td>
                        4
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Asuna,gmchan,Deco,Mopu,Rein,Renzi,Tank,marunasu,YoshiKZ,Yuuki,Donaldo
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/17
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Shun,Kapera,Ayane,Maru,Koua,Babe,Peach(Minato),Dogma,Kuro,Alessio,Veras
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/18
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Toku,Satopy,YoshiKZ,Michael,Jonny,Crisis,Yasuyoshi,Soba,Yuuki,Ayane,Koua
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/18
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        Losing the table
                    </td>
                    <td>
                        Yamaguchi,Uerin,Hiduke,Nuno,wis,Rigel,Kocchi,Koua,Aku,Charichan,Zeta,Finite
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/18
                    </th>
                    <td>
                        2
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,KJ,Nathan,Dorasu,Yoshitaka,Ammo,Deco,Kotoran,Spica,Uerin,YoshiKZ,Maq
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/19
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Peach,Koua,YoshiKZ,Toku,Renzi,Kotoran,Deco,Yoshitaka,Rigel,Dorasu,Donaldo
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/19
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Rockk,Erika,Dorasu,Decopon,Yuni,Trace,Raf,Kapera,Negima,Renzi,Yuuki
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/19
                    </th>
                    <td>
                        2
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Toku,Uerin,Donaldo,Decopon,Renzi,Goreinu,YoshiKZ,Mapu,Hina,Trace,Kapera
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/19
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Draggy,Starboi,Nobu,Michael,Jam,Matt,Tank,Shun,Tatsuya,Trace,Bawp
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/19
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Hizumi,Yoshitaka,Tank,Dogma,Soda,Kocchi,Spica,Maru,Peach,Finite,Lena
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/20
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Maru,Mopu,Peach,YoshiKZ,Dogma,Yoshitaka,Hizumi,Lena,Ryoko,Michael,Donaldo
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/20
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Sneak,Lena,MK,Nobu,snk,Ayane,Kocchi,Mikey,Maq,Death spear,Fiona,Vanillaice
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/22
                    </th>
                    <td>
                        2
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Hiduke,Tatsuya,EZ,Dongira,Rigel,Soda,Spica,Yasuyoshi,Uerin,Tank,Eimii
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/22
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Maru,Fiona,Nyoni,Yorunagi,Vanillaice,Finite,Uerin,Tank,Tatsuya,Rigel,Soba
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/22
                    </th>
                    <td>
                        3
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Kapera,Erika,Vanillaice,Hyp,Totori,Soda,Roast,Maru,Milano,Hiduke,Fuku,Yamaguchi
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/23
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Vase,marunasu,Negima,JEX,Tank,Koua,Hiduke,YoshiKZ,Peach,Finite,Roast
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/24
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        Virgin vs Play Boy
                    </td>
                    <td>
                        Yamaguchi,Sasha,wis,Fiona,Tatsuya,EZ,Hiduke,Maru,Fuku,Babe,Yorunagi,Eimii
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/25
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamguchi,Amphas,Cloud,Peach,Totori,JEX,YoshiKZ,Michael,Ryoko,Donaldo,gmchan,Maru
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/27
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Michael,Cloud,Maru,Lion,Yuuki,Dorasu,Kotoran,gmchan,Peach,KouBG,Koua
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/27
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        Western vs Eastern
                    </td>
                    <td>
                        Yamaguchi,Lion,Finite,Dorasu,Maru,Yorunagi,Marunasu,Spica,Godiva,Michael,Amphas,Totori
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/28
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        High Score
                    </td>
                    <td>
                        Yamaguchi,Az,Finite,Ruka,Tank,Koua,Renzi,Michael,YoshiKZ,Fuku,EZ,Soba
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/28
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        Kura vs Sushiro
                    </td>
                    <td>
                        Yamaguchi,Az,Peach,Nobu,Roast,gmchan,Bobchan,EZ,Renzi,Fuku,(?),(?)
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/30
                    </th>
                    <td>
                        2
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Trace,Reo,Michael,Aku,Finite,Sutapa,Soba,Fiona,Goreinu,Hina,Uerin
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/30
                    </th>
                    <td>
                        2
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Az,Homyu,Finite,Foo,Milano,Saa,Miya,Dorasu,Hina,Toku,Goreinu
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/30
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Peach,Negima,Finite,Reo,Roast,Goreinu,Minoru,Asuna,Dorasu,Tank,Nyoni
                    </td>
                </tr>
                <tr>
                    <th>
                        2020/12/31
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Saber,Dan,Reo,Totori,Michael,Hizumi,YoshiKZ,Godiva,KJ,Sasha,marunasu
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/1/4
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Reo,Shun,Atama,marunasu,Tank,Hiduke,Fuku,Dorasu,Donaldo,Invade,Godiva
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/1/4
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Erika,Hiduke,Mopu,Dorasu,Donaldo,EZ,Trace,marunasu,Fuku,Michael,Godiva
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/1/8
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,YoshiKZ,Roast,Finite,gmchan,Hiduke,Foo,Roka,Babe,Fuku,Rockk,EZ
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/1/8
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Hiduke,Fuku,Raf,gmchan,Rockk,Mopu,Bobchan,YoshiKZ,Michael,Foo,(?)
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/1/8
                    </th>
                    <td>
                        3
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Michael,EZ,Bobchan,Totori,Dorasu,Remi,Fuku,Mopu,YoshiKZ,Yuuki,Kitani
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/1/20
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,YoshiKZ,Maq,Finite,Pr,Peach,JEX,Yuuki,Foo,wis,oga,Renzi
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/1/20
                    </th>
                    <td>
                        3
                    </td>
                    <td>
                        Omaru
                    </td>
                    <td>
                        Yamaguchi,Maq,Miya,Bawp,Nuno,Lilac,Foo,Ryofu,wis,Pr,Renzi,Hiduke
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/1/26
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Kurato,Asuna,Foo,Finite,Miya,Rein,Hyp,Fuku,Pr,EZ,Rigel
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/1/27
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Foo,Hyp,Peach,Tank,Milano,Ryofu,marunasu,Pr,Trace,Donaldo,oga
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/2/3
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Tank,Kapera,Pr,Ryofu,Peach,Woco,Negima,Finite,Yasuyoshi,Sigure,Hiduke
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/3/6
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Babe,Deco,Raf,tank,Yasuyoshi,Satopy,Solar,Uerin,Hizumi,Cloud,yuiazu
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/3/28
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Az,Babe,Deco,Asuna,Satopy,Sasha,Bobchan,Hizumi,EZ,marunasu,Hiduke,Minato
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/4/2
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Hizumi,YoshiKZ,Ryofu,Fuku,Minato,EZ,Hyp,Hiduke,Uerin,Tank,Asuna,Donaldo
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/4/4
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        Omaru
                    </td>
                    <td>
                        Asuna,Babe,Bobchan,Deco,Koua,Sasha,Yuiazu,Hiduke,Hizumi,YoshiKZ,Raf,Dogma
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/5/2
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Negima,Shamo,Reo,Deco,Bobchan,Fiona,Az,Michael,Asuna,Hiduke,Rockk,Koua
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/5/2
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Asuna,Hiduke,Bobchan,Az,Luise,Rein,Sasha,Negima,Deco,Godiva,Reo,Saber
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/5/13
                    </th>
                    <td>
                        3
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Shamo,EZ,Uerin,Totori,Satopy,YoshiKZ,Asuna,Donaldo,Deco,Babe,Nishino
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/5/14
                    </th>
                    <td>
                        2
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Hiduke,Kapera,Shino,EZ,Finite,Nishino,Fiona,Rigel,Heggu,Satopy,Babe
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/5/14
                    </th>
                    <td>
                        2
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamaguchi,Hiduke,Sasha,EZ,Finite,Babe,Shino,Heggu,Satopy,Nishino,Foo,Saa
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/5/16
                    </th>
                    <td>
                        2
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        oga,Paprika,Totori,Hyp,Hiduke,EZ,Deco,Asuna,Omochi,Saa,Shino,Yasuyoshi
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/5/16
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Raf,Reo,Hiduke,Asuna,EZ,Donaldo,Bobchan,Dorasu,Satopy,Hyp,Sumo,Fuku
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/5/17
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Nuclear,Hiduke,Tank,Rockk,oga,Fuku,Bobchan,Hyp,Shino,Satopy,Paprika,Sabo
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/5/17
                    </th>
                    <td>
                        2
                    </td>
                    <td>
                        Omaru
                    </td>
                    <td>
                        Nuclear,YoshiKZ,Nuno,Totori,Bobchan,Yasuyoshi,Shino,Dorasu,Hiduke,Sabo,Satopy,Donaldo
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/5/18
                    </th>
                    <td>
                        2
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Yamagchi,Shamo,oga,Satopy,Hina,Hiduke,Deco,Yasuyoshi,EZ,Uerin,Donaldo,Asuna
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/5/18
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Fuku,Totori,Satopy,Deco,Kotoran,Mopu,Hiduke,Shamo,YoshiKZ,oga,Asuna,Yasuyoshi
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/5/19
                    </th>
                    <td>
                        2
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Rigel,Asuna,Satopy,Nishino,Type,Yasuyoshi,Shamo,Uerin,Akuril,Sumo,Totori,oga
                    </td>
                </tr>
                <tr>
                    <th>
                        2021/5/19
                    </th>
                    <td>
                        6
                    </td>
                    <td>
                        
                    </td>
                    <td>
                        Satopy,Shino,Yasuyoshi,EZ,Type,Hyp,Asuna,Kotoran,Hiduke,Nuno,Nishino,Deco
                    </td>
                </tr>
            </tbody>
        </table>
    </section>
</body>
</html>
