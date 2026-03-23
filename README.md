Payback Coupon Auto-Activator
Dieses Skript automatisiert das Einlösen von Payback-Coupons. Anstatt jeden Coupon mühsam einzeln anzuklicken, sucht das Skript alle verfügbaren Coupons auf der Seite, aktiviert sie gleichzeitig und lädt die Seite automatisch neu, um eventuell nachgerückte Coupons ebenfalls zu erfassen (insgesamt 3 Durchläufe).

Es gibt zwei Möglichkeiten, dieses Skript zu nutzen: Automatisiert über die Browser-Erweiterung Tampermonkey oder manuell als Lesezeichen (Bookmarklet).

Methode 1: Installation mit Tampermonkey (Empfohlen)
Mit Tampermonkey läuft das Skript vollautomatisch und übersteht auch das Neuladen der Seite.
Lade dir die kostenlose Browser-Erweiterung Tampermonkey herunter (verfügbar für Chrome, Firefox, Edge, Safari).
Öffne die Datei payback-auto.user.js hier in diesem GitHub-Repository.
Klicke oben rechts auf den Button Raw (Rohdaten).
Tampermonkey erkennt das Skript nun automatisch und öffnet einen neuen Tab. Klicke dort auf Installieren.
Rufe die Payback-Coupon-Seite auf. Das Skript startet sofort von alleine, aktiviert alle Coupons, wartet 2 Sekunden und lädt die Seite bis zu 3-mal neu.

Methode 2: Als Lesezeichen / Bookmarklet (Ohne Erweiterung)
Wer keine zusätzliche Browser-Erweiterung installieren möchte, kann eine leicht abgewandelte Version des Codes als Lesezeichen speichern.
Wichtiger Hinweis zu dieser Methode: Da ein Lesezeichen nach einem Seiten-Reload aus dem Arbeitsspeicher des Browsers gelöscht wird, funktioniert die automatische Wiederholung hier nicht. Du musst das Lesezeichen nach dem Neuladen der Seite jedes Mal manuell neu anklicken.
Mache einen Rechtsklick auf deine Lesezeichenleiste im Browser und wähle Lesezeichen hinzufügen (oder Seite hinzufügen).
Gib dem Lesezeichen einen Namen, zum Beispiel Payback Aktivator.
Kopiere den folgenden Code-Block komplett und füge ihn in das Feld URL (oder Adresse) ein:
javascript:(async function(){const b=document.querySelectorAll('button[data-testid$="-not_activated"]');if(b.length>0){b.forEach(btn=>btn.click());setTimeout(()=>location.reload(),2000);}else{alert("Keine Coupons mehr gefunden.");}})();
Speichere das Lesezeichen.
Logge dich bei Payback ein, gehe auf die Coupon-Seite und klicke auf dein neues Lesezeichen. Die Seite lädt danach neu, klicke bei Bedarf einfach nochmal darauf.

⚠️ Sicherheitshinweis:
Dieses Skript agiert ausschließlich lokal in deinem Browser. Es liest keine Passwörter aus und sendet keine Daten an Dritte. Die Nutzung erfolgt dennoch auf eigene Gefahr.
