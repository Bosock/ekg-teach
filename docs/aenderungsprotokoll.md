# Änderungsprotokoll EKG-Teach

Jede inhaltliche Änderung mit Begründung und Quelle (Herausgeber, Datum bzw. Version). Grundlage für die fachärztliche Freigabe (Prof. Dr. med. R. Gradaus) vor dem Lehreinsatz.

---

## Version 0.3 · 30.10.2026 · fachliche Korrekturen

Auslöser: inhaltliche und fachliche Prüfung von v0.2 am 29.10.2026 (Prüfbericht im Projekt „EPU Simulator“).

### Rhythmus und Morphologie

| Nr. | Karte / Bereich | v0.2 | v0.3 | Quelle |
|---|---|---|---|---|
| 1 | „Vorhofflattern (atypisch, clockwise)“ | als *nicht isthmusabhängig* bezeichnet | umbenannt in **„Vorhofflattern (typisch, im Uhrzeigersinn)“**: derselbe isthmusabhängige Kreis, umgekehrte Richtung; positive F-Wellen in II/III/aVF, breite negative in V1. Karten-ID `atrial_flutter_cw` | Bun SS et al., Res Rep Clin Cardiol 2019;10:7–17 (Dove Press, 26.04.2019); LITFL Atrial Flutter (ECG Library) |
| 2 | Vorhofflattern gegen den Uhrzeigersinn | nur inferiore Polarität genannt | ergänzt: positive F-Wellen in V1 | LITFL Atrial Flutter |
| 3 | AV-Block II° Wenckebach | PR-Zuwachs konstant (160→220→280 ms) → RR konstant, obwohl die Karte eine RR-Verkürzung behauptet | abnehmender Zuwachs (160→260→310 ms); RR verkürzt sich vor dem Ausfall (gemessen 1100→1050 ms) | LITFL AV Block 2nd degree Mobitz I (Buttner R) |
| 4 | Linksschenkelblock | septale q-Zacken in I/aVL/V5/V6 sichtbar, R nicht breit/gekerbt – widersprach dem Kartentext | eigene Morphologie: keine lateralen q, breites, mittig gekerbtes R in I/aVL/V5/V6, rS/QS in V1–V3; strenge QRS-Kriterien im Text | LITFL LBBB; Surawicz B et al., JACC 2009;53:976–981 (AHA/ACCF/HRS); Strauss DG et al., Am J Cardiol 2011;107:927–934 |
| 5 | Rechtsschenkelblock | keine breite S-Zacke lateral | eigene Morphologie: rSR′ in V1–V3, breite plumpe S-Zacke in I/aVL/V5/V6 | LITFL RBBB; Surawicz et al. 2009 |
| 6 | Monomorphe VT | wirkte im 12-Kanal-Bild schmal, normale R-Progression | QRS 170 ms, Nordwest-Achse, negative Konkordanz V1–V6 (keine RS-Komplexe), diskordante T-Wellen, dissoziierte P-Wellen (AV-Dissoziation); Hinweis „mit oder ohne Puls“ | LITFL Ventricular Tachycardia – Monomorphic VT; LITFL ECG Axis Interpretation; ERC 2025 Adult ALS (Resuscitation 2025;215:110769) |
| 7 | „SA-Block II° / Sinusarrest“ | eine Karte für zwei Befunde, nur SA-Block dargestellt | getrennt: **SA-Block II° (Typ II)** mit Pause = 2 × PP und **Sinusarrest** mit Pause ohne ganzzahligen Bezug (2,55 × PP) | LITFL Sinoatrial Exit Block; FIU/Gordon Center, UMedic ECG Cases „Sinus Arrest and SA Block“ |
| 8 | Multifokale atriale Tachykardie | Karte nannte variable PR, erzeugt wurde konstante PR | PR je Schlag variabel (120–200 ms); Kriterien präzisiert | LITFL Multifocal Atrial Tachycardia |
| 9 | Linksposteriorer Hemiblock | Untertitel „überdrehter Rechtstyp“ bei Voreinstellung +110° (= Rechtstyp) | „Achse +90° bis +180° (Rechtstyp bis überdrehter Rechtstyp)“ | Surawicz et al. 2009 (Kriterien nach my-ekg.com); DocCheck Flexikon „Lagetyp“ (Stand 27.08.2026) |
| 10 | Kategorie „Reanimationsrhythmen“ | enthielt VT und Torsade, die mit Puls auftreten können | „Ventrikuläre Rhythmen / Herzstillstand“ | ERC 2025 Adult ALS |

### Lagetyp und QT-Zeit

| Nr. | Bereich | v0.2 | v0.3 | Quelle |
|---|---|---|---|---|
| 11 | Lagetyp-Schaltflächen | „Indifferenz“ bei +60° (Grenze zum Steiltyp) | Schaltflächen in der Mitte ihres Bereichs; Anzeige des Lagetyps zum eingestellten Winkel; Nordwest-Achse ergänzt; Regler −180° bis +180° | DocCheck Flexikon „Lagetyp“; LITFL ECG Axis Interpretation |
| 12 | Voreinstellung der Achse | +60° (Grenzwert) in 20 Karten | +50° (Indifferenztyp) | wie Nr. 11 |
| 13 | QTc | nur Bazett, feste Grenzen (< 440 normal, ≥ 470 verlängert) | Bazett und Fridericia; Grenzen nach AHA/ACCF/HRS 2009: verlängert ≥ 450 ms (Männer) / ≥ 460 ms (Frauen), deutlich ≥ 500 ms, kurz ≤ 390 ms; Hinweis auf Überkorrektur durch Bazett bei hoher Frequenz | Rautaharju PM et al., Circulation 2009;119:e241–e250 (nach Stanford Rogers Lab QTc Calculator); CredibleMeds/AZCERT „The Effect of Heart Rate on QT“ (Stand nicht angegeben) |
| 14 | QT-Voreinstellungen | Sinusbradykardie 440 ms bei 45/min, Wenckebach 380 ms bei 60/min (QTc nach Bazett ≤ 390 ms, würde nun als „kurz“ gelten) | 460 ms bzw. 400 ms | wie Nr. 13 |

### Medikamente

| Nr. | Bereich | v0.2 | v0.3 | Quelle |
|---|---|---|---|---|
| 15 | Atropin | „aktuelle Erstlinie 1 mg“ (AHA-Dosis, obwohl das Tool sich auf ERC 2025 beruft) | ERC 2025: 500 µg i.v./i.o., alle 3–5 min bis 3 mg; AHA 2025 1 mg als Vergleich; paradoxe Verlangsamung < 0,5 mg; unwirksam bei infranodalem Block, Schrittmacherstimulation nicht verzögern | ERC Guidelines 2025 Adult Advanced Life Support, Resuscitation 2025;215:110769; Resuscitation Council UK, Adult ALS Guidelines (27.10.2025); OpenExamPrep, „Atropine Dosing, Indications & Block Limitations“ (Stand 07/2026, nach AHA 2025) |
| 16 | Isoprenalin | pauschal „Torsade-Prophylaxe und elektrischer Sturm“ | Zweitlinie bei Bradykardie (ERC 2025, Start 5 µg/min); erworbene, pausenabhängige Torsade; elektrischer Sturm bei idiopathischem Kammerflimmern (ESC 2022) und Brugada-Syndrom; Vorsicht/meiden bei angeborenem LQTS Typ 1/2 | ERC 2025 Adult ALS; ACC „2022 ESC Guidelines for Ventricular Arrhythmias: Key Points“ (Crawford TC, 02.09.2022); El-Battrawy I et al., Front Cardiovasc Med 2022 (zitiert ESC 2015, Klasse IIa); Tannenbaum L, emDocs „ECG Pointers: Long Intervals and Squiggly Lines“ (29.07.2026) |
| 17 | Kaliumchlorid | Dosisoption „Bolus“ (legte die i.v.-Bolusgabe als reguläre Option nahe) | „zu schnelle Gabe (Fehlanwendung)“; Voreinstellung 100-ml-Infusion | Australian Council for Safety and Quality in Health Care, Medication Alert 1 „Intravenous Potassium Chloride can be fatal if given inappropriately“ (10/2003) |

### Validator und QM-Selbsttest

| Nr. | Änderung | Begründung |
|---|---|---|
| 18 | Neue Kartenkriterien, gemessen am Signal unabhängig von den Erzeugungsparametern (globaler QRS-Beginn/-Ende aus allen 12 Ableitungen): keine lateralen q (LSB), rSR′ in V1 und breite terminale S lateral (RSB), negative Konkordanz und Nordwest-Achse (VT), RR-Verkürzung und PR-Zunahme (Wenckebach), konstante PR (Mobitz II), Pause = 2 × PP (SA-Block), Pause ohne ganzzahligen Bezug (Sinusarrest), keine feste P-QRS-Kopplung (Vorhofflimmern) | Der Validator prüfte in v0.2 vor allem, ob der Generator seine eigene Vorgabe einhält; morphologische Aussagen der Karten waren ungeprüft. |
| 19 | Gegenproben im QM-Selbsttest: jedes neue Kriterium muss an einer unpassenden Karte scheitern (11 Gegenproben) | Nachweis, dass jede Prüfung tatsächlich scheitern kann („wer prüft den Prüfer“). |
| 20 | Vorhofflimmern: Prüfung „keine regulären P-Wellen“ ersetzt durch „keine feste P-QRS-Kopplung“ | Die alte Prüfung bestand nur, weil die Flimmerwellen bewusst unter die Erkennungsschwelle gelegt waren; sie scheiterte bereits bei einer kleinen Achsänderung. |
| 21 | Medikamenten-Vorlagen werden mit den Karten-Voreinstellungen erzeugt, nicht mit den aktuellen Reglerstellungen | In v0.2 hingen die Wellenformen der Medikamenten-Ansicht davon ab, welche Pathologie und welche Regler zuvor eingestellt waren. |

### Sonstiges

- README: Versionsangabe korrigiert; Aussage „Akzeptanz wird im Browser-Speicher abgelegt“ entfernt (der Code speichert nichts).

### Prüfergebnis (Headless-Browser, 30.10.2026)

- Selbst-Konsistenz: 31/31 Karten 15/15
- Gegenproben: 11/11 korrekt nicht erfüllt
- Einthoven (II = I + III): max. Abweichung 0,079 mV (Toleranz < 0,15)
- Sprungstellen-Prüfung: 23/23 ohne Diskontinuität
- Regressionslauf: 308 Kombinationen Rhythmus × Medikament, 0 Fehler

### Offen (nicht Teil dieser Version)

- Echtes atypisches (nicht isthmusabhängiges) Vorhofflattern als eigene Karte
- AV-Block III° mit junktionalem Ersatzrhythmus (schmaler QRS)
- Brugada-Karte; Ajmalin-Dosierung gewichtsbezogen prüfen
- Rhythmus- und Leitungsbefunde werden im gemeinsamen Werkzeug mit dem EPU-Simulator künftig mechanistisch erzeugt (Integrationskonzept vom 29.10.2026)
- Fachärztliche Freigabe ausstehend
