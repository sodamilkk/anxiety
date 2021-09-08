intro-play-button
(...51)

ΠΑΙΞΕ! publish("intro-to-game-1"); Game.OVERRIDE_CHOICE_LINE=true;

intro-start
(...500)

clearText()

n3: Οπότε, πριν αρχήσουμε, πώς θα θέλεις να διαβάσεις;

publish("show_options_bottom")

intro-start-2
n3: Τώρα, ας αρχίσει η ιστορία μας...

publish("hide_tabs");
clearText();
(...1000)

publish("intro-to-game-2")

n2: ΑΥΤΟΣ ΕΙΝΑΙ ΕΝΑΣ ΑΝΘΡΩΠΟΣ

(...600)

clearText()

(...300)

publish("intro-to-game-3")

act1
SceneSetup.act1();
publish("hide_tabs");
music('battle', {volume:0.5});
(...300)

n: ΚΑΙ ΑΥΤΟ ΕΙΝΑΙ ΤΟ ΑΓΧΟΣ ΤΟΥ ΑΝΘΡΩΠΟΥ

n: ΕΣΥ ΕΙΣΑΙ ΤΟ ΑΓΧΟΣ

(#act1_normal)

act1_normal
hong({body:"putaway"});
sfx("rustle");
Game.OVERRIDE_TEXT_SPEED = 1.5;
h: Όχι. Όχι, με τίποτα, δεν ακούω. Θα δω το κινητό μου.

sfx("rustle2");
hong({body:"phone1", mouth:"neutral", eyes:"neutral"})
n: Η ΔΟΥΛΕΙΑ ΣΟΥ ΕΙΝΑΙ ΝΑ ΠΡΟΣΤΑΤΕΨΕΙΣ ΤΟΝ ΑΝΘΡΩΠΟ ΑΠΟ ΤΟ ΚΙΝΔΥΝΟ

bb({eyes:"look", mouth:"small_lock", body:"fear"})

b: Αμάν! Ξωδεύεις τη ζωή σου στο Τουίτερ! Ξανα!

bb({eyes:"normal", mouth:"normal", body:"normal"});
hong({eyes:"annoyed"});
h: Ναι και εγώ αναρωτιέμαι γιατί δε κάθομαι να ακούω τις σκέψεις μου πιο συχνά.

hong({eyes:"neutral"});

n: ΓΡΗΓΟΡΑ, ΠΡΟΕΙΔΟΠΟΙΗΣΕ ΤΟΥΣ ΓΙΑ ΕΝΑ ΚΙΝΔΥΝΟ!

bb({eyes:"look"});
Αχ, δες αυτό το φρικτό νέο!

Ρε συ, μήπως αυτό το τουίτ μιλάει για 'μας;

Για δές, ενα βιντεάκι με γάτα που πίνει γάλα

act1d_milk
hong({mouth:"smile", eyes:"surprise"});

h: Χαχα ναι ειναι χαριτωμένο, εγώ--

hong({mouth:"shock", eyes:"shock"});
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 1.8;
b: ΟΙ ΓΑΤΕΣ ΔΕ ΜΠΟΡΟΥΝ ΝΑ ΧΩΝΕΨΟΥΝΕ ΓΑΛΑ ΚΑΙ ΕΙΜΑΣΤΕ ΑΠΑΝΘΡΩΠΟΙ ΠΟΥ ΜΑΣ ΑΡΕΣΕΙ Η ΚΑΚΟΠΟΙΗΣΗ ΖΩΩΝ
