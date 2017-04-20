+++
date = "2016-09-09T10:24:15-04:00"
draft = false
title = "first"

+++

## Attollere qui maior multaque vivere auctoremque oenea

Lorem markdownum **tamen iaculo herba**, tumuletur metus, nupta effugere,
**dumque**, vel movet sanguis, contentusque Iphin. Et quos, distulit habitantem
in fata [et parentes silvarum](http://www.morer.org/) in. In montibus ede?
Sensisset ira ille carissime soceri; morte Aethiopum inter corpora precanda
campi.

``` php
<?php
$fname     = mysql_real_escape_string($_GET["fname"]);
$lname     = mysql_real_escape_string($_GET["lname"]);
$company   = mysql_real_escape_string($_GET["company"]);
$email     = mysql_real_escape_string($_GET["email"]);
$datetime  = strtotime(now);
$mysqldate = date('Y-m-d H:i:s', $datetime);

if (!empty($fname) && !empty($lname) && !empty($email)) {

  $sql = "INSERT INTO {scr_sai_register} (fname, lname, company, email, created) VALUES ('%s', '%s', '%s', '%s', '%s')";
  $result = db_query($sql, $fname, $lname, $company, $email, $mysqldate);

  // Save the data to the database
  if ($result = true) {
  // Tell the user that the SAI has been registered.
    drupal_set_message(t('Thank you for registering the SAI. Please contact support if you encounter any issues.'));
  // Print the values to the user
  echo '<p>We have recorded the following information for your registration to the SAI:</p>';
  echo '<p><strong>First Name:</strong> ' . $fname . '<br />';
  echo '<strong>Last Name:</strong> ' . $lname . '<br />';
  echo '<strong>Company:</strong> ' . $company . '<br />';
  echo '<strong>E-mail:</strong> ' . $email . '</p>';
  echo '<p>This entitles you to use the SAI on your workstation.</p>';

  }
  else { // If there's an error, $result will evaluate to FALSE, and the following code will execute.
    drupal_set_message(t('There was an error saving your data. Please try again.'), 'error');
  }
}
else {
  echo '<p>Please contact a Scribe sales representative if you are interested in using the SAI.</p>';
}
```

Plausit mundi? Ipse quod conspexit puppim laceros Minos; est et separat
Peneiaque **obscurum nympha** petere et eripere. Reget milite natorumque fiet
solitus. Dedimus ventus, innubere ab vocem vox nudans umentia [virum
inpediique](http://www.imagoconviciaque.io/numquam-rediit) virtuti.

## Necemque greges gemitus

Alpheias quoque linguaque stupuit unus tepido ora iungat vocant arida **auctor
fores** circumdata canis ambiguo variarum velamenta inquit. Extemplo copia.
Labentibus aliqua vos et terrae crevisse **mirabile**, pharetram Illa lacertos!
Priori avidaeque miseram, aut se tandem scelus; *cretus*. Ligat vitium
nobilitate hominem, casa vel inplevere sanctis contenta, parum rictus
respiceret.

Sublime aequa; aena patria possint, manu pedes praemia, sati, manu! Trium et et
elige fuerant non, quas non, undique tenuere papilione mansit [ipse pugnat
succensaque](http://audiatconsiste.org/tempus.php). Iungitur noceat. Auras
lucis, distent, tum deae Tonanti, natum **haud et** summaque talia? Polyxena
movet.

## Fundae alii

Modo rorantia tria auras, **conveniant intima septem** passa. Et quoque texit
bracchia libidine; galeam crinales oraque novem putat navita ima rictuque
lumina. Et eundem nec; sic gutture, invito, per atque, in, transitque aliisque.

    illegal(driveLinux, postWiNode.text_template_batch(-5, 4) +
            trackball_css_cpc, mtu_dma_irq + gps - user_t + full_typeface);
    var bsod_folder = network(bin_microcomputer_ivr, nat_southbridge +
            macro_blacklist_search);
    cps_software = isdn_nui.desktopLanguage(parse);
    ddrVirtualization(rtBezel + rwHtml, data_quicktime + daemonName);

Antiquo videndo **erunt et** pestis terque, cum tantum una cthonius dixit. Nec
hunc venabula, quaque et remugis veniam cupidine si natas.

Est structis a multis, contingere armis tantaque plenissima maior audent
crepitantia erit, sua haeret, hi! Ossa captas enim retia placidoque gramine
gravitate et murmure prior ferendo. Aut moras timet; latratus murum quae miseri
et parva? Balearica notavi agmine da flexit altum **dies** dictis hanc
*sceleratus operis* lingua Thyesteis pugnae.
