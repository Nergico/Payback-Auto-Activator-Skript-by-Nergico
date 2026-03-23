Payback Coupon Auto-Activator

Dieses Skript automatisiert das Einlösen von Payback-Coupons. Anstatt jeden Coupon mühsam einzeln anzuklicken, sucht das Skript alle verfügbaren Coupons auf der Seite, aktiviert sie gleichzeitig und lädt die Seite automatisch neu, um eventuell nachgerückte Coupons ebenfalls zu erfassen (insgesamt 3 Durchläufe).

Es gibt zwei Möglichkeiten, dieses Skript zu nutzen: Automatisiert über die Browser-Erweiterung Tampermonkey oder manuell als Lesezeichen (Bookmarklet).

Methode 1: Installation mit Tampermonkey (Empfohlen)

Mit Tampermonkey läuft das Skript vollautomatisch und übersteht auch das Neuladen der Seite.

Lade dir die kostenlose Browser-Erweiterung Tampermonkey herunter (verfügbar für Chrome, Firefox, Edge, Safari).
Stelle sicher, dass Tampermonkey die Berechtigung hat, Skripte auszuführen. Gehe dazu – je nach Browser – in die Eigenschaften/Details deiner Tampermonkey-Erweiterung und aktiviere dort "Benutzerskripts zulassen" (oder eine ähnliche Formulierung).
Gehe auf GitHub unter "Releases" und kopiere dir das Tampermonkey-Skript.
Klicke in deinem Browser auf die Tampermonkey-Erweiterung und wähle "Neues Skript erstellen".
Füge den kopierten Code dort ein und speichere das Skript (Datei > Speichern).
Rufe die Payback-Coupon-Seite auf. Nun solltest du an der Tampermonkey-Erweiterung erkennen, dass ein Skript für die aktuelle Seite ausgeführt wird.
Das Skript startet sofort von alleine, aktiviert alle Coupons, wartet 2 Sekunden und lädt die Seite bis zu 3-mal neu.
Wenn du nicht möchtest, dass die Coupons automatisch aktiviert werden, deaktiviere das Skript einfach über das Menü der Tampermonkey-Erweiterung.

Methode 2: Als Lesezeichen / Bookmarklet (Ohne Erweiterung)

Wer keine zusätzliche Browser-Erweiterung installieren möchte, kann eine leicht abgewandelte Version des Codes als Lesezeichen speichern.

Wichtiger Hinweis zu dieser Methode: Da ein Lesezeichen nach einem Seiten-Reload aus dem Arbeitsspeicher des Browsers gelöscht wird, funktioniert die automatische Wiederholung hier nicht. Du musst das Lesezeichen nach dem Neuladen der Seite jedes Mal manuell neu anklicken.
Mache einen Rechtsklick auf deine Lesezeichenleiste im Browser und wähle Lesezeichen hinzufügen (oder Seite hinzufügen).
Gib dem Lesezeichen einen Namen, zum Beispiel Payback Coupon Aktivator.
Kopiere den dafür vorgesehenen Code-Block komplett und füge ihn in das Feld URL (oder Adresse) ein:
Logge dich bei Payback ein, gehe auf die Coupon-Seite und klicke auf dein neues Lesezeichen. Die Seite lädt danach neu. Klicke bei Bedarf einfach noch einmal darauf. Erfahrungsgemäß muss dies 2-3x wiederholt werden, damit alle Coupons aktiviert sind.

⚠️ Sicherheitshinweis
Dieses Skript agiert ausschließlich lokal in deinem Browser. Es liest keine Passwörter aus und sendet keine Daten an Dritte. Die Nutzung erfolgt dennoch auf eigene Gefahr.
