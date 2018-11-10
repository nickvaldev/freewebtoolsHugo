+++
appNum = "app1"
draft = false
title = "Υπολογισμός ΦΠΑ"
description = "Yπολογιστε το ποσό με προσαρμοσμένο τον ΦΠΑ, και επίσης μπορείτε να τον αφαιρέσετε από το ποσό."
categories = "Oικονομικά"
tags = "ΦΠΑ"
[inputs]
  number = 2
  haveSpan = ["1","1"]
  spanContents = ['&euro;',"%"]
  labels = ["Ποσό","Ποσοστό"] 
  placeholders = ["Δώστε το ποσό","24"]
  step = ["any","any","1"]
  min = [0,0,1]
  max = []
[buttons]
  number = 2
  contents = ["Πρόσθεση ΦΠΑ","Αφαίρεση ΦΠΑ"]
[selects]
  number = 0
  titles = ""
  values = [""]
  texts = [""]
[textareas]
  number = 0
  counters = [2]
  countersTexts = [["Λέξεις","Χαρακτήρες"]]
  placeholder = ["Γράψτε το κείμενο ή κάντε το copy / paste"]
  rows = [10]
  hasCopyButtons = ['1']
  copyButtonsTexts = ["Αντιγράψτε το κείμενο"]  
[results]
  columns = 3
  titles = ["Ποσό με ΦΠΑ","ΦΠΑ 24%","Ποσό χωρίς ΦΠΑ"]
  spanContents = ["&euro;49.6","&euro;9.6","&euro;40"]
  spanContentsSigns = [""]
+++


Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean.

A small river named Duden flows by their place and supplies it with the necessary regelialia. It is a paradisematic country, in which roasted parts of sentences fly into your mouth.
