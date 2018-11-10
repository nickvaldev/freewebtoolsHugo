+++
appNum = "app5"
draft = false
title = "Μετατροπή Μεγεθών Θερμοκρασίας"
description = "Υπολογιστής μετατροπής θερμοκρασίας. Συμπεριλαμβάνει βαθμούς Κελισίου, Φαρεναίτ και Κέλβιν."
categories = "Μετατροπές"
tags = ["Θερμοκρασία", "Μετατροπή"]
[inputs]
  number = 1
  haveSpan = ["0"]
  spanContents = [""]
  labels = ["Θερμμοκρασία"] 
  placeholders = ["Γράψτε την θερμοκρασία που θέλετε να μετατρέψετε"]
  step = ["any"]
  min = ["-70"]
  max = ["60"]
[buttons]
  number = 1
  contents = ["Υπολογισμός"]
[selects]
  number = 2
  titles = ["Από","ΣΕ"]
  values = ["celsius","fahrenheit","kelvin"]
  texts = ["Κελισίου (Celcius)","Φαρεναίτ (Fahrenheit)","Κέλβιν (Kelvin)"]
[textareas]
  number = 0
  counters = [2]
  countersTexts = [["Λέξεις","Χαρακτήρες"]]
  placeholder = ["Γράψτε το κείμενο ή κάντε το copy / paste"]
  rows = [10]
  hasCopyButtons = ['1']
  copyButtonsTexts = ["Αντιγράψτε το κείμενο"]  
[results]
  columns = 2
  titles = ["Κελισίου (Celcius)","Φαρεναίτ (Fahrenheit)"]
  spanContents = ["20","7.55"]
  spanContentsSigns = ["°C","℉"]
+++

Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean.

A small river named Duden flows by their place and supplies it with the necessary regelialia. It is a paradisematic country, in which roasted parts of sentences fly into your mouth.
