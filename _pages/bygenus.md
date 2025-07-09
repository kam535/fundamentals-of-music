---
layout: page
permalink: /bygenus/
title: by genus
description: A breakdown of the different tunings organized by genera
nav: true
nav_order: 5
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

h1.bygenus_name {
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

.toc_bygenus {
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

<div class="toc_bygenus">
    <h2>Table of Contents</h2>
    <ul>
        <li>
            <a href="#Diatonic">Diatonic</a>
            <ul role="list">
                <li><a href="#d_b">Boethius</a></li>
                <li><a href="#d_x">Aristoxenus</a></li>
                <ul role="list">
                    <li><a href="#shd_x">Sharp Diatonic</a></li>
                    <li><a href="#sod_x">Soft Diatonic</a></li>
                </ul>
                <li><a href="#d_y">Archytas</a></li>
            </ul>
        </li>
        <li>
            <a href="#Chromatic">Chromatic</a>
            <ul role="list">
                <li><a href="#c_b">Boethius</a></li>
                <li><a href="#c_x">Aristoxenus</a></li>
                <ul role="list">
                    <li><a href="#tc_x">Tonic Chromatic</a></li>
                    <li><a href="#hc_x">Hemiolic Chromatic</a></li>
                    <li><a href="#sc_x">Soft Chromatic</a></li>
                </ul>
                <li><a href="#c_y">Archytas</a></li>
            </ul>
        </li>
        <li>
            <a href="#Enharmonic">Enharmonic</a>
            <ul role="list">
                <li><a href="#e_b">Boethius</a></li>
                <li><a href="#e_x">Aristoxenus</a></li>
                <li><a href="#e_y">Archytas</a></li>
            </ul>
        </li>
    </ul>
</div>

<h1 class="bygenus_name" style="padding-top:50px" id="Diatonic">Diatonic</h1>


<table> <!-- cellspacing 0 to support IE6 and IE7 -->
    <colgroup>
        <col span="1" style="width: 60%;">
        <col span="1" style="width: 40%;">
    </colgroup>
    <tr>
        <td colspan="2" id="d_b"><h3>Boethius</h3></td>
    </tr>
    <tr>
        <td>individual diatonic tetrachord - Boethius's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_d_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct diatonic tetrachords - Boethius's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_d_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct diatonic tetrachords - Boethius's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_d_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire diatonic scale, with synemmenon tetrachord - Boethius's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_d_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire diatonic scale, with diezeugmenon tetrachord - Boethius's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_d_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="d_x"><h3>Aristoxenus</h3></td>
    </tr>
    <tr>
        <td colspan="2" id="shd_x"><h4>Sharp Diatonic</h4></td>
    </tr>
    <tr>
        <td>individual sharp diatonic tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_shd_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct sharp diatonic tetrachords - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_shd_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct sharp diatonic tetrachords - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_shd_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire sharp diatonic scale, with synemmenon tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_shd_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire sharp diatonic scale, with diezeugmenon tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_shd_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="sod_x"><h4>Soft Diatonic</h4></td>
    </tr>
    <tr>
        <td>individual soft diatonic tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sod_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct soft diatonic tetrachords - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sod_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct soft diatonic tetrachords - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sod_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire soft diatonic scale, with synemmenon tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sod_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire soft diatonic scale, with diezeugmenon tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sod_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="d_y"><h3>Archytas</h3></td>
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
</table>

<h1 class="bygenus_name" style="padding-top:50px" id="Chromatic">Chromatic</h1>


<table> <!-- cellspacing 0 to support IE6 and IE7 -->
    <colgroup>
        <col span="1" style="width: 60%;">
        <col span="1" style="width: 40%;">
    </colgroup>
    <tr>
        <td colspan="2" id="c_b"><h3>Boethius</h3></td>
    </tr>
    <tr>
        <td>individual chromatic tetrachord - Boethius's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_c_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct chromatic tetrachords - Boethius's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_c_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct chromatic tetrachords - Boethius's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_c_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire chromatic scale, with synemmenon tetrachord - Boethius's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_c_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire chromatic scale, with diezeugmenon tetrachord - Boethius's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_c_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="c_x"><h3>Aristoxenus</h3></td>
    </tr>
    <tr>
        <td colspan="2" id="tc_x"><h4>Tonic Chromatic</h4></td>
    </tr>
    <tr>
        <td>individual tonic chromatic tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_tc_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct tonic chromatic tetrachords - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_tc_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct tonic chromatic tetrachords - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_tc_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire tonic chromatic scale, with synemmenon tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_tc_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire tonic chromatic scale, with diezeugmenon tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_tc_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="hc_x"><h4>Hemiolic Chromatic</h4></td>
    </tr>
    <tr>
        <td>individual hemiolic chromatic tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_hc_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct hemiolic chromatic tetrachords - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_hc_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct hemiolic chromatic tetrachords - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_hc_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire hemiolic chromatic scale, with synemmenon tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_hc_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire hemiolic chromatic scale, with diezeugmenon tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_hc_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="sc_x"><h4>Soft Chromatic</h4></td>
    </tr>
    <tr>
        <td>individual soft chromatic tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sc_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct soft chromatic tetrachords - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sc_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct soft chromatic tetrachords - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sc_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire soft chromatic scale, with synemmenon tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sc_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire soft chromatic scale, with diezeugmenon tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_sc_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="c_y"><h3>Archytas</h3></td>
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
                <source src="../assets/audio/y_c_scale_full_s.mp3" type="audio/mp3">
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
</table>

<h1 class="bygenus_name" style="padding-top:50px" id="Enharmonic">Enharmonic</h1>


<table> <!-- cellspacing 0 to support IE6 and IE7 -->
    <colgroup>
        <col span="1" style="width: 60%;">
        <col span="1" style="width: 40%;">
    </colgroup>
    <tr>
        <td colspan="2" id="e_b"><h3>Boethius</h3></td>
    </tr>
    <tr>
        <td>individual enharmonic tetrachord - Boethius's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_e_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct enharmonic tetrachords - Boethius's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_e_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct enharmonic tetrachords - Boethius's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_e_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire enharmonic scale, with synemmenon tetrachord - Boethius's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_e_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire enharmonic scale, with diezeugmenon tetrachord - Boethius's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/b_e_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="e_x"><h3>Aristoxenus</h3></td>
    </tr>
    <tr>
        <td>individual enharmonic tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_e_tetra_solo.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two conjunct enharmonic tetrachords - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_e_tetra_j.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>two disjunct enharmonic tetrachords - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_e_tetra_dj.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td>entire enharmonic scale, with synemmenon tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_e_scale_full_s.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
        <tr>
        <td>entire enharmonic scale, with diezeugmenon tetrachord - Aristoxenus's tuning</td>
        <td>
            <audio controls>
                <source src="../assets/audio/x_e_scale_full_d.mp3" type="audio/mp3">
                Your browser does not support the audio tag.
            </audio>
        </td>
    </tr>
    <tr>
        <td colspan="2" id="e_y"><h3>Archytas</h3></td>
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