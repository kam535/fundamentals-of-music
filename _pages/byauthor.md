---
layout: page
permalink: /byauthor/
title: by author
description: A breakdown of the different tunings organized by attributed author
nav: true
nav_order: 4
---
<style>
.container_by_author {
  display: grid;
  grid-template-columns: 60% auto;
  padding: 10px;
}
.container_by_author > div {
 background-color: #f1f1f1;
  border: 3px solid var(--global-bg-color);
  padding: 20px;
}
.container_by_author > div > audio {
    background-color: var(--global-divider-color);
    border-radius: 5px;
    padding: 10px;
}
.audio_right_column {
    display: grid;
    align-items: center;
    justify-items: center;
    padding: 0px;
}
table {
    width: 100%;
    padding-top: 10px;
    padding-bottom: 100px;
}
table, th, td {
  border: 5px solid var(--global-bg-color);
  background-color: var(--global-footer-text-color);
  border-collapse: collapse;
  scroll-margin-top: 500px;
}
th, td {
    padding: 20px;
    scroll-margin-top: 85px;

    &:hover {
    color: var(--global-theme-color);
    background-color: var(--globalfooter-link-color);
  }
    
}

h1.byauthor_name {
    text-align: right;
    color: var(--global-theme-color);
    scroll-margin-top: 50px;
}
h3 {
    text-align: center;
    text-decoration-line: underline;
    scroll-margin-top: 500px;

    &:hover {
    color: var(--global-theme-color);
    background-color: var(--globalfooter-link-color);
  }   
}

audio {
     background-color: var(--global-divider-color);
     border-radius: 5px;
     padding: 10px;
     width: auto;
    }

.toc_byauthor {
    display: table;
    padding: 20px;
    background-color: var(--global-divider-color);
    border-radius: 5px;
    text-align: 
}

ul {
    list-style-type: none;
}

</style>

<div class="toc_byauthor">
    <h2>Table of Contents</h2>
    <ul>
        <li>
            <a href="#boethius">Boethius</a>
            <ul role="list">
                <li><a href="#b_d">Diatonic</a></li>
                <li><a href="#b_c">Chromatic</a></li>
                <li><a href="#b_e">Enharmonic</a></li>
            </ul>
        </li>
        <li>
            <a href="#aristoxenus">Aristoxenus</a>
            <ul role="list">
                <li><a href="#x_shd">Sharp Diatonic</a></li>
                <li><a href="#x_sod">Soft Diatonic</a></li>
                <li><a href="#x_tc">Tonic Chromatic</a></li>
                <li><a href="#x_hc">Hemiolic Chromatic</a></li>
                <li><a href="#x_sc">Soft Chromatic</a></li>
                <li><a href="#x_e">Enharmonic</a></li>
            </ul>
        </li>
        <li>
            <a href="#archytas">Archytas</a>
            <ul role="list">
                <li><a href="#y_d">Diatonic</a></li>
                <li><a href="#y_c">Chromatic</a></li>
                <li><a href="#y_e">Enharmonic</a></li>
            </ul>
        </li>
    </ul>
</div>

 <h1 class="byauthor_name" style="padding-top:50px" id="boethius">Boethius</h1>


<table> <!-- cellspacing 0 to support IE6 and IE7 -->
    <colgroup>
        <col span="1" style="width: 60%;">
        <col span="1" style="width: 40%;">
    </colgroup>
    <tr>
        <td colspan="2" id="b_d"><h3>Diatonic</h3></td>
    </tr>
    <tr>
        <td>individual diatonic tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_d_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct diatonic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_d_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct diatonic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_d_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire diatonic scale, with synemmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_d_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire diatonic scale, with diezeugmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_d_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="b_c"><h3>Chromatic</h3></td>
    </tr>
    <tr>
        <td>individual chromatic tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_c_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct chromatic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_c_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct chromatic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_c_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire chromatic scale, with synemmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_d_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire chromatic scale, with diezeugmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_c_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="b_e"><h3>Enharmonic</h3></td>
    </tr>
    <tr>
        <td>individual enharmonic tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_e_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct enharmonic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_e_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct enharmonic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_e_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire enharmonic scale, with synemmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_e_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire enharmonic scale, with diezeugmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_e_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
</table>


<!-- ARISTOXENUS SECTION -->


<h1 id="aristoxenus" class="byauthor_name" style="padding-top:50px">Aristoxenus</h1>


<table> <!-- cellspacing 0 to support IE6 and IE7 -->
    <colgroup>
        <col span="1" style="width: 60%;">
        <col span="1" style="width: 40%;">
    </colgroup>
    <tr>
        <td colspan="2" id="x_shd"><h3>Sharp Diatonic</h3></td>
    </tr>
    <tr>
        <td>individual sharp diatonic tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_shd_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct sharp diatonic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_shd_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct sharp diatonic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_shd_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire sharp diatonic scale, with synemmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_shd_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire sharp diatonic scale, with diezeugmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_shd_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="x_sod"><h3>Soft Diatonic</h3></td>
    </tr>
    <tr>
        <td>individual soft diatonic tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sod_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct soft diatonic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sod_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct soft diatonic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sod_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire soft diatonic scale, with synemmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sod_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire soft diatonic scale, with diezeugmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sod_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="x_tc"><h3>Tonic Chromatic</h3></td>
    </tr>
    <tr>
        <td>individual tonic chromatic tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_tc_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct tonic chromatic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_tc_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct tonic chromatic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_tc_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire tonic chromatic scale, with synemmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_tc_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire tonic chromatic scale, with diezeugmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_tc_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="x_hc"><h3>Hemiolic Chromatic</h3></td>
    </tr>
    <tr>
        <td>individual hemiolic chromatic tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_hc_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct hemiolic chromatic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_hc_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct hemiolic chromatic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_hc_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire hemiolic chromatic scale, with synemmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_hc_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire hemiolic chromatic scale, with diezeugmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_hc_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="x_sc"><h3>Soft Chromatic</h3></td>
    </tr>
    <tr>
        <td>individual soft chromatic tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sc_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct soft chromatic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sc_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct soft chromatic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sc_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire soft chromatic scale, with synemmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sc_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire soft chromatic scale, with diezeugmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sc_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="x_e"><h3>Enharmonic</h3></td>
    </tr>
    <tr>
        <td>individual enharmonic tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_e_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct enharmonic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_e_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct enharmonic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_e_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire enharmonic scale, with synemmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_e_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire enharmonic scale, with diezeugmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_e_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
</table>

<!-- Archytas starts here -->
 <h1 class="byauthor_name" style="padding-top:50px" id="archytas">Archytas</h1>


<table> <!-- cellspacing 0 to support IE6 and IE7 -->
    <colgroup>
        <col span="1" style="width: 60%;">
        <col span="1" style="width: 40%;">
    </colgroup>
    <tr>
        <td colspan="2" id="y_d"><h3>Diatonic</h3></td>
    </tr>
    <tr>
        <td>individual diatonic tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/y_d_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct diatonic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/y_d_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct diatonic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/y_d_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire diatonic scale, with synemmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/y_d_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire diatonic scale, with diezeugmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/y_d_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="y_c"><h3>Chromatic</h3></td>
    </tr>
    <tr>
        <td>individual chromatic tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/y_c_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct chromatic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/y_c_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct chromatic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/y_c_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire chromatic scale, with synemmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/y_d_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire chromatic scale, with diezeugmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/y_c_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="y_e"><h3>Enharmonic</h3></td>
    </tr>
    <tr>
        <td>individual enharmonic tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/y_e_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct enharmonic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/y_e_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct enharmonic tetrachords</td>
        <td>
            <audio controls>
                <source src="../assets/audio/y_e_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire enharmonic scale, with synemmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/y_e_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire enharmonic scale, with diezeugmenon tetrachord</td>
        <td>
            <audio controls>
                <source src="../assets/audio/y_e_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
</table>
