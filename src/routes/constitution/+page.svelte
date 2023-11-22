<script>
    import { dues } from '$lib/utils/helper';
    let one;
    let two, twoOne, twoTwo, twoThree;
    let three, threeOne, threeTwo, threeThree, threeFour, threeFive;
    let four, fourOne, fourTwo, fourThree;
    let five, fiveOne, fiveTwo, fiveThree;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree, sevenFour;
    let eight, eightOne, eightTwo, eightThree, eightFour;
    let nine, nineOne, nineTwo, nineThree, nineFour, nineFive;
    let ten;
    let eleven;
    
    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
   <h1 class="noUnderscore">JEDEN VERDAMMTEN SONNTAG LEAGUE CONSTITUTION</h1>
    
    <h2 class="noUnderscore">INHALTSVERZEICHNIS</h2>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(one)}>Artikel I: EINLEITUNG</h3>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(two)}>Artikel II: LEAGUE COMMISSIONER</h3>
	
		<h4 class="noUnderscore clickable" on:click={() => goToSection(twoOne)}>Das Amt des Commissioners</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoTwo)}>Einschränkungen</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoThree)}>Vorgeschriebene Strafen</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(three)}>Artikel III: CLUBS UND MANAGER</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeOne)}>Aktuelle Manager</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeTwo)}>Abstimmungen in der Offseason</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeThree)}>Abstimmung in der Regular Saison</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeFour)}>Regularien der Abstimmungen</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeFive)}>Austritt von Managern</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(four)}>Artikel IV: LEAGUE SETTINGS</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourOne)}>Allgemeine Einstellungen der Liga</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourTwo)}>Siege und Tiebreaker</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourThree)}>Trades und Waiver-Picks</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(five)}>Artikel V: JEDEN VERDAMMTEN SONNTAG SNAKE DRAFT</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveOne)}>Ankündigung</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveTwo)}>Draft Order Determination</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveThree)}>Regeln des Drafts</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(six)}>Artikel VI: FREE AGENCY, FAAB-BUDGETS UND ROSTER MANAGEMENT</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixOne)}>Free Agent und Waiver Wire</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixTwo)}>Verantwortlichkeiten der Manager</h4>
		<h4 class="noUnderscore clickable" on:click={() => goToSection(sixThree)}>FAAB (Free Agent Acqusition Budget)</h4>
    
     <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Artikel VII: TRADES</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenOne)}>Regeln</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenTwo)}>Verbotene Trades</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenThree)}>Trade Deadline</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenFour)}>FAAB-Einsatz</h4>
    
     <h3 class="noUnderscore clickable" on:click={() => goToSection(eight)}>Artikel VIII: PLAYOFFS</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightOne)}>Zeit</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightTwo)}>Teilnahme</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightThree)}>Tiebreaker</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightFour)}>Bestimmungen</h4>
    
     <h3 class="noUnderscore clickable" on:click={() => goToSection(nine)}>Artikel IX: REGELVERSTÖßE</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineOne)}>Art der Straftaten</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineTwo)}>Einleitung eines Ordnungswidrigkeitenverfahrens</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineThree)}>Regelverstöße</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineFour)}>Strafen</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineFive)}>Schiedsrichter</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(ten)}>Anhang "A": FINANZEN</h3>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(eleven)}>Anhang "B": VERSIONSHISTORIE</h3>
    
    <hr />
    
     <h2 class="sectionHeading" bind:this={one}>Artikel 1: EINLEITUNG</h2>
     <p>Diese Constitution ist eine Vereinbarung zwischen den Managern der Liga. Von diesen Managern akzeptiert jeder die Regeln und Pflichten, die in dieser Vereinbarung festgesetzt wurden und verpflichtet sich, diese zu befolgen. Die Constitution bleibt auf unbestimmte Zeit in Kraft.</p>
    

     <h2 class="sectionHeading" bind:this={two}>Artikel II: LEAGUE COMMISSIONER</h2>
     
	 <h3 bind:this={twoOne}>Das Amt des Commissioners</h3>
		<ol>
			<li>Das Amt des Commissioners ist hiermit eingerichtet.</li>
			<li>Zu den Aufgaben des Commissioners gehören:</li>
				<ol type="a">
					<li>als Verwaltungschef und Streitschlichter der Liga zu fungieren.</li>
					<li>Fragen der Mitglieder zu beantworten und auftretende Probleme zu lösen.</li>
					<li>auf Beschwerde oder auf eigene Initiative jede Handlung oder Transaktion zu untersuchen, die eventuell nicht mit den Regeln dieser Constitution vereinbar ist. Dafür darf er Manager dazu bewegen, zu einem Problem Stellung zu nehmen und anschließend eventuelle vorgesehenen Sanktionen zu verhängen.</li>
					<li>welche Präventiv- oder Strafmaßnahmen unter den jeweiligen Umständen für die Handlung oder Transaktion angemessen sind und gegebenenfalls Maßnahmen gegen Manager oder andere Personen zu ergreifen.</li>
					<li>eine Person zu ernennen, die dem Amt des Commissioners offiziell beigeordnet ist, soweit dies erforderlich ist.</li>
					<li>Entscheidungen in Bezug auf Regelauslegungen, Verwaltung, Trades oder Disziplinarmaßnahmen treffen, soweit dies erforderlich sein kann.</li>
					<li>alle Änderungen dieser Verfassung in <a href="#eins">Anhang B "Änderungshistorie"</a> festzuhalten.</li>
				</ol>
			<li>Amtszeitbeschränkungen und Wahlen</li>			
				<ol type="a">
					<li>Der Commissioner übt sein Amt ohne Mindestdauer aus. Die Manager der Liga haben in jeder Offseason die Möglichkeit, über einen neuen Commissioner abzustimmen.</li>
					<li>Die Wahl eines Commissioners erfolgt mit einfacher Mehrheit. Jeder Manager hat eine (1) Stimme. Bei Stimmengleichheit findet mindestens einmal wöchentlich eine weitere Wahl statt, bis ein Commissioner gewählt ist.</li>
					<li>Der Commissioner kann jederzeit (auch in der Season) mit einer Zweidrittel-Mehrheit abgewählt werden. Gleichzeitig muss ein neuer Commissioner mit absoluter Mehrheit gewählt werden. Kommt diese Mehrheit nicht zustande, bleibt der Commissioner bis auf Weiteres im Amt.</li>
					<li>Der Commissioner ist zu jeder Zeit gleichgestellt mit jedem anderen Manager der Liga. Er hat sich an alle Regeln zu halten, unabhängig der in Artikel II, Abschnitt 2 beschriebenen Sonderrechte.</li>
				</ol>
		</ol>

	<h3 bind:this={twoTwo}>Einschränkungen</h3>
		<ol start="4">
			<li>Ungeachtet der Bestimmungen dieses Abschnitts darf der Commissioner keine Maßnahmen ergreifen und keine Änderung dieser Constitution vornehmen, die eine Abstimmung der Manager erfordern, wie in Artikel III, Abschnitt 2 dargelegt.</li>
			<li>Jede ergriffene Maßnahme des Commissioners kann nach folgendem Verfahren wieder aufgehoben werden:</li>			
				<ol type="a">
					<li>Manager, die von der Entscheidung betroffen sind, sind nicht berechtigt, an einem Vote zur Aufhebung der -Commissioner-Entscheidung teilzunehmen.</li>
					<li>Die Entscheidung kann neu überprüft werden, wenn mindestens die Hälfte der Manager (ausgenommen die beteiligten Manager) gegen die Entscheidung des Commissioners stimmt. Damit kann der Fall neu überprüft oder neu abgestimmt werden. <u>Dieser Antrag auf Abstimmung muss innerhalb einer Woche nach der Entscheidung in den Message Boards gestellt werden.</u></li>
					<li>Der Commissioner und alle betroffenen Parteien können bei den Managern der Liga nach Belieben zur Unterstützung einer Abstimmung werben.</li>
					<li>Die Entscheidung des Commissioners kann bei der Abstimmung nur mit einer Zweidrittel-Mehrheit der wahlberechtigten Manager aufgehoben werden.</li>
					<li>Wenn eine solche Mehrheit nicht erreicht wird, bleibt die Entscheidung des Commissioners bestehen. <u>Zur Klarstellung: Dies schließt weitere Aktionen des Commissioners gegen denselben Manager oder zum selben Thema nicht aus.</u></li>
				</ol>
		</ol>
		<p><u>Auslegungsbemerkung:</u> <i>Zum Beispiel kann der Commissioner gemäß Artikel II, Abschnitt 6, Absatz c) entscheiden, dass Manager X aufgrund von illegalem Verhalten (z.B. illegal Lineup) einen Punktabzug für den Spieltag erhält. Diese Entscheidung wird an einem Dienstag um 12:35 Uhr in den Message Boards veröffentlicht. Sechs Manager der Liga (ohne die beteiligten Manager) (mehr als 50%) beantragt beim Commissioner eine erneute Überprüfung oder eine erneute Abstimmung gemäß Artikel II, Abschnitt 5, Absatz b), und zwar vor Ablauf der Frist um 12:35 Uhr am folgenden Dienstag.</i></p>
		<p><i>Der Commissioner weigert sich, dies noch einmal zu überdenken, und daher findet eine Abstimmung statt. Mehr als zwei Drittel der Manager stimmen dafür, dass die Entscheidung aufgehoben werden soll. Die Entscheidung des Commissioners ist damit offiziell aufgehoben. Der Commissioner entscheidet dann gemäß Artikel II, Abschnitt 6, Absatz e), dass der angeklagte Manager stattdessen mit einer Reduzierung der Waiver-Priority bestraft wird. Nur zwei Manager beantragen dazu eine Überprüfung dieser Entscheidung. Da dies weniger als 50% sind, um einen gültigen Antrag zu stellen, hat diese Entscheidung bestand und der angeklagte Manager wird darauf hin mit einer Reduzierung der Waiver-Priority bestraft.</i></p>

	<h3 bind:this={twoThree}>Vorgeschriebene Strafen</h3>
		<ol start="6">
			<li>Im Falle einer illegalen Aktion, können folgende Straf- oder Disziplinarmaßnahmen gegen die Manager erlassen werden:</li>
				<ol type="a">
					<li>Eine formelle Warnung;</li>
					<li>Eine Rückgängigmachung, Änderung oder Ablehnung eines Trades oder Waiver-Picks;</li>
					<li>Punktabzug für den Spieltag;</li>
					<li>Ein Verfall eines zuvor festgelegten Draft-Picks;</li>
					<li>Eine Reduzierung der Waiver Priority;</li>
					<li>Suspendierung oder Rauswurf eines Managers aus der Liga;</li>
					<li>Abzug oder Verfall des FAAB-Budgets;</li>
					<li>Andere Maßnahmen, die der Commissioner für angemessen hält.</li>
				</ol>
			<li>Entscheidungen des Commissioners über Strafen für die Manager müssen formell in den Boards veröffentlicht werden.</li>
		</ol>
    
    
    <h2 class="sectionHeading" bind:this={three}>Artikel III: CLUBS UND MANAGER</h2>
    
    <h3 bind:this={threeOne}>Aktuelle Manager</h3>
    <ol>
         <li>Die Manager jedes Clubs werden wie folgt festgelegt:</li>
            <ol type="a">
                <li>Marcus – Show Me Your TDs</li>
                <li>Chris – Smack Ya’ll Team</li>
                <li>Markus Hembes – TeamBayPackers</li>
                <li>Markus Flohr – Barfuß Bethlehem</li>
                <li>Bö – Hail to the GOAT</li>
                <li>Ecki – Eckis Eleven</li>
                <li>David Mehrfeld – Unicorn Brittle Bones</li>
                <li>David Schwarz – Superdogs</li>
                <li>Nico – Stay calm and OMAHA!</li>
                <li>Marten – Rasenrammler Rügen</li>
                <li>Janosch – Sorenson GOAT</li>
                <li>Manu – Turned Goff Again</li>
            </ol>
    </ol>
    
    <h3 bind:this={threeTwo}>Abstimmungen in der Offseason</h3>
    <ol start="2">
         <li>In jeder Offseason sind die Manager verpflichtet, an Abstimmungen teil zu nehmen, die Folgendes umfassen können:</li>
            <ol type="a">
                <li>die Wahl eines Commissioners;</li>
                <li>Der Betrag des jährlichen FAABs eines Clubs;</li>
                <li>Änderung an dieser Constitution. Dies kann Folgendes umfassen:</li>
                    <ol type="i">
                        <li>Die Erweiterung der Liga;</li>
                        <li>Aktualisierung der Ligaeinstellungen und Regeln, wie in Artikel IV definiert; und</li>
                        <li>Aktualisierung der Draft-Regularien.</li>
                    </ol> 
            </ol>
    </ol>
    <p>Absatz a) bis c) bedarf einer einfachen Mehrheit durch eine Abstimmung; Absatzes c) kann bei Bedarf und Bedeutung der Änderung mit einer Zwei-Drittel-Mehrheit festgesetzt werden. Nach Ablauf des Abstimmungsfensters werden alle Stimmen gezählt und eine Entscheidung vom Commissioner gemäß der ihm in Artikel II, Abschnitt 2 Absatz f) erteilten Befugnis getroffen.</p>

    <h3 bind:this={threeThree}>Abstimmungen in der Regular Season</h3>
    <ol start="3">
         <li>Während der Regular Saison sind die Manager verpflichtet, an Abstimmungen teil zu nehmen, die Folgendes umfassen können:</li>
            <ol type="a">
                <li>Umfragen, die vom Commissioner zur Orientierung verlangt werden; und</li>
                <li>Überprüfung der Entscheidungen des Commissioners innerhalb der Regular Saison, wie in Artikel II, Abschnitt 5 dargelegt.</li>
            </ol>
		 <li>Diese Constitution kann, während der Regular Saison, nur durch einstimmigen Beschluss durch eine Abstimmung der Manager geändert werden. Die Abstimmungen bleibt für 3 Tage nach der Erstellung geöffnet. Nach Ablauf des Abstimmungsfensters werden alle Stimmen gezählt und eine Entscheidung vom Commissioner gemäß der ihm in Artikel II, Abschnitt 2 Absatz f) erteilten Befugnis getroffen.</li>
    </ol>
    
    <h3 bind:this={threeFour}>Regularien der Abstimmungen</h3>
    <ol start="5">
         <li>Es besteht eine Abstimmungspflicht in der Regular Season- und Offseason. Falls ein Manager nicht abstimmt, verfällt dessen Stimme unwiderruflich.</li>
         <li>Ausnahmen, bei der eine 100% Abstimmungsquote erreicht werden muss, sind: Abwahl-/ Wahl des Commissioners, Abstimmung in Bezug auf die Constitution, Ernennung/Ersetzen neuer Mitglieder, Ort und Uhrzeit des Drafts.</li>
    </ol>
    
    <h3 bind:this={threeFive}>Austritt von Managern</h3>
    <ol start="7">
         <li>Manager können sich jederzeit zwischen Beginn der Offseason und dem 15. August innerhalb dieser Offseason ohne Strafe aus der Liga zurückziehen. Ihre Clubs bleiben bestehen und ein neuer Manager kann durch die anderen Manager gefunden und ernannt werden.</li>
         <li>Jeder Manager, der zwischen dem 15. August und dem Beginn der folgenden Offseason in einem bestimmten Jahr aussteigt, verliert sein Buy-In-Guthaben.</li>
         <li>Neue Manager haben die Möglichkeit, den Club eines zurückgetretenen Managers umzubenennen.</li>
    </ol>
    
    
    <h2 class="sectionHeading" bind:this={four}>Artikel IV: LEAGUE SETTINGS</h2>
    
    <h3 bind:this={fourOne}>Allgemeine Einstellungen der Liga</h3>
    <ol>
         <li>Die Liga ist eine wöchentliche Head-to-Head-Liga, die auf Sleeper gehosted wird.</li>
         <li>Das Scheduling der Liga wird von den internen Systemen von Sleeper festgelegt, vom Commissioner überprüft und an die Bye-Weeks angepasst.</li>
            <ol type="a">
                <li>Jeder spielt einmal gegen jeden anderen.</li>
                <li>Da hierfür nur elf (11) Wochen nötig sind, werden die Weeks 6, 10 und 14 nach vorgegebenen Methoden ausgelost:</li>
                    <ol type="i">
                        <li>Week 6: Kicker Punkte aus Week 5 (1. vs. 10.; 2. vs. 9; etc.)</li>
                        <li>Week 10: Bench Punkte aus Week 9 (1. vs. 10.; 2. vs. 9; etc.)</li>
                        <li>Week 14: Gesamt-Platzierungen: 1. vs. 2.; 3. vs. 4; etc.</li>
                    </ol>
				<li>Zusätzlich findet ein imagineres Spiel gegen den League-Median statt. Dabei wird der Mittelwert aus den Punkten des 6. und des 7. eines Spieltags (Median) gebieldet. Liegen die eigenen erzielten Punkte darüber, so erhält man einen weitern Win, liegen sie darunter, so erhält man ein weiteres Loss.</li>	
            </ol>
         <li>Die Scoring-Kategorien und zugehörigen Punkte für die Liga lauten wie folgt:</li>
             <ol type="a">
                 <li>Passing: Passing Yards (0,04) / TD Pass (4) / Interceptions Throw (-2) / 2pt Pass-ing Conversions (2)</li>
                 <li>Rushing: Rushing Yards (0.1) / TD Rush (6) / 2pt Rushing Conversion (2)</li>
                 <li>Receiving: Receiving Yards (0.1) / Reception (0.5) / TD Reception (6) / 2pt Re-ceiving Conversion (2)</li>
                 <li>Sonstiges: Kickoff Return TD (6) / Punt Return TD (6) / Fumble recovered for TD (6) / Total Fumbles (-0.5) / Total Fumbles Lost (-1.5) / Fumble Return TD (6) / 2 Point Return TD (2)</li>
                 <li>Kicking: PAT Made (1) / PAT Missed (-2) / Points per FG Yard (0.1) / FG Missed (0-39 yds) (-2) / FG Missed (40-49 yds) (-1)</li>
                 <li>Defense und Special Teams: Sack (1) / INT Return TD (6) / Fumble Return TD (6) / Blocked Punt oder FG Return for TD (6) / Blocked Punt, PAT oder FG (2) / Interception (2) / Fumble Recovered (1) / Safety (2) / Sack (1) / Forced Fumble (1) / 0 Points Allowed (10) / 1-6 Points Allowed (8) / 7-13 Points Allowed (6) / 14-20 Points Allowed (3) / 21-27 Points Allowed (1) / 35+ Points Allowed (-2) / Less Than 100 Total Yards Allowed (5) / 100-199 Total Yards Allowed (3) / 200-299 Total Yards Allowed (2) / 350-399 Total Yards Allowed (-1) / 400-449 Total Yards Allowed (-3) / 450-499 Total Yards Allowed (-5) / 500-549 Total Yards Al-lowed (-6) / 550+ Total Yards Allowed (-7)</li>
             </ol> 
        <li>Der Roster setzt sich wie folgt zusammen:</li>
             <ol type="a">
                <li>1 Starting Quarterback (QB); Kein Maximum</li>
                <li>2 Starting Running Backs (RB); Kein Maximum</li>
                <li>2 Starting Wide Receivers (WR); Kein Maximum</li>
                <li>1 Starting Tight End (TE); Kein Maximum</li>
                <li>2 Starting Flex (RB/WR/TE);</li>
                <li>1 Starting Defense/Special Team (D/ST); Kein Maximum</li>
                <li>1 Starting Kicker (K); Kein Maximum</li>
                <li>6 Bench (BN);</li>
             </ol>
        <li>Während der Regular Saison besteht dieser Kader maximal aus 16 Spielern (zuzüglich zwei IR-Spots).</li>
    </ol>

    <h3 bind:this={fourTwo}>Siege und Tiebreaker</h3>
    <ol start="6">
         <li>Wöchentliche Head-to-Head-Matchups werden von dem Team mit der höheren Punktzahl für diese bestimmte Woche nach Abzug aller etwaigen Strafen gemäß Artikel IX, Abschnitt 8 gewonnen.</li>
         <li>Matchups, die mit einem Unentschieden enden, werden als Unentschieden mit Ausnahme von Spielen in den Playoffs und des Championship-Games wie in Artikel VIII, Abschnitt 6 gewertet.</li>
    </ol>
    
    <h3 bind:this={fourThree}>Trades und Waiver-Picks</h3>
    <ol start="8">
         <li>Jeder Club ist berechtigt, jede Saison eine unbegrenzte Anzahl von Trades und/oder Add/Drops auf der Waiver zu tätigen.</li>
	 <li>Jeder Club hat vor der Saison ein entsprechendes FAAB-Budget erhalten. Dies muss für die Waiver-Adds benutzt werden.</li>
         <li>Jeder Trade unterliegt keinem Überprüfungszeitraum. Manager haben jedoch die Möglichkeit durch eine Abstimmung den Trade als illegal oder unfair zu melden.</li>
    </ol>
    
     
    <h2 class="sectionHeading" bind:this={five}>Artikel V: JEDEN VERDAMMTEN SONNTAG SNAKE DRAFT</h2>
    
    <h3 bind:this={fiveOne}>Ankündigung</h3>
    <ol>
         <li>Das Datum und die Uhrzeit werden auf Sleeper, auf der Website und in WhatsApp veröffentlicht und jedem Eigentümer per E-Mail mitgeteilt.</li>
         <li>Das Startdatum jedes nachfolgenden Snake Drafts wird vom Commissioner in Absprache mit den Managern spätestens zwei (2) Wochen vor Beginn der regulären NFL-Saison festgelegt, und soll spätestens einen (1) Tag vor dem Opening Kickoff und mit einer Frist zur Kenntnisnahme von mindestens sieben (7) Tagen für die Clubs durchgeführt werden.</li>
    </ol>
    
    <h3 bind:this={fiveTwo}>Draft Order Determination</h3>
    <ol start="3">
         <li>Jedes Jahr wird es eine neue Auslosung der Draft-Positionen geben. Dabei ist der 1st Pick dem Gewinner des Loser-Brackets des vorhergehenden Jahres bereits zugeordnet (wie in Artikel VIII, Abschnitt 9 festgelegt). Diese Position kann aber auf freiwilliger Basis zurückgegeben werden, um an der Auslosung teilnehmen zu können. Der Gewinner des Vorjahres besitzt dabei automatisch den letzten Pick im Draft.</li>
    </ol>
    
    <h3 bind:this={fiveThree}>Regeln des Drafts</h3>
    <ol start="4">
         <li>Der Draft unterliegt dem automatisierten Prozess von Sleeper und ist ein Snake Draft.</li>
	 <li>Jedoch kann der Draft auf anderen Plattformen oder im Offline-Format stadtfinden. Die Ergebnisse werden anschließend vom Commissioner in Sleeper eingetragen.</li>
    </ol>

    <h2 class="sectionHeading" bind:this={six}>Artikel VI: FREE AGENCY, FAAB-BUDGETS UND ROSTER MANAGEMENT</h2>
    
    <h3 bind:this={sixOne}>Free Agent und Waiver Wire</h3>
    <ol>
         <li>Free Agent Spieler werden über die wöchentliche Waiver Wire erworben. Die Waiver-Wire-Reihenfolge wird anhand des eingesetzten FAAB-Budgets für den jeewiligen Spieler festgelegt, wie in Artikel VI, Abschnitt 9-14 beschrieben.</li>
         <li>Es gibt kein Saison-Limit an Free-Agent/Waiver-Picks.</li>
         <li>Jeder neue Free Agent bleibt 24 Stunden lang auf der Waiver Wire, um allen Teams die Möglichkeit zu geben, auf diesen zu bieten.</li>
    </ol>
    
    <h3 bind:this={sixTwo}>Verantwortlichkeiten der Manager</h3>
    <ol start="4">
         <li>Manager müssen jederzeit ein komplettes (legal) Team aufstellen.</li>
         <li>Manager dürfen verletzte Spieler oder IR-Spieler nicht zum Kick-Off in ihrer aktiven Aufstellung belassen. Kick-Off bedeutet, dass mindestens ein Spieler in der aktiven Aufstellung spielt. Ebenso dürfen Spieler, die auf einem IR-Spot sind, nachdem sie den Out oder IR-Status verloren haben, nicht auf diesem Spot zum Kick-Off bleiben.</li>
         <li>Verletzt sich ein Spieler vor einem Spätspiel, oder ist bis dahin der Status noch nicht geklärt, wird die Frist für die Manager zum wechseln des Spielers auf 23 Uhr des Spieltages festgelegt. Ändert sich nach dieser Uhrzeit der Status eines Spieler, so wird der Manager nicht für ein illegal Line-Up verantwortlich gemacht.</li>
         <li>Die Nichteinhaltung der in den Abschnitten 4,5 und 6 festgelegten Verantwortlichkeiten führt dazu, dass der Manager nach Ermessen des Commissioners gemäß Artikel II, Abschnitt 6 bestraft wird und gemäß Artikel II, Abschnitt 5 überprüfbar ist.</li>
         <li>Darüber hinaus, wenn ein Manager für einen Zeitraum von mehr als zwei Wochen inaktiv ist, stellt dies einen Regelbruch im Sinne von Artikel IX dar.</li>
    </ol>
    
   <h3 bind:this={sixThree}>FAAB (Free Agent Acqusition Budget)</h3>
    <ol start="9">
         <li>Das Free Agent Acqusition Budget (FAAB) definiert eine fiktive Währung, die jeder Manager vor der Season erhält. Dieses kann für Spieler auf der Waiver-Wire geheim ausgegeben werden.</li>
         <li>Das höchste Gebot eines Managers auf einen Spieler erhält den Zuschlag.</li>
         <li>Bei einem gleichem Gebot, erhält ein Manager durch einen automatischen Prozess den Zuschlag (jedes Mal, wenn ein Manager ein Gebot gewinnt, rutscht dieser an das Ende der Waiver-Wire. Jeder andere rutscht darauf hin einen Platz nach oben, bis auch diese ein Gebot gewinnen)</li>
		 <li>Jedes Mal, wenn ein Gebot gewonnen wird, reduziert sich das vor der Saison festgelegte Budget des jeweiligen Managers um den gebotenen Betrag. Die Gebote können vor dem Waiver-Durchlauf nicht von anderen Managern eingesehen werden. Erst nach dem Durchlauf sind die FAAB-Einsätze für alle sichtbar.</li>
		 <li>Folgende Einstellungen werden getroffen:</li>
		  <ol type="a">
                <li>Jedes Team erhält zum Anfang jeder Saison ein FAAB-Budget von 200$. Es gibt kein Maximum des Budgets. Über die Saison kann FAAB-Budget anhand von Trades erhalten werden.</li>
                <li>Das FAAB-Budget kann getraded werden (Bsp.: Manager X kann Spieler A und 50$ für Spieler B traden.).</li>
                <li>Das FAAB-Budget wird für jede Saison zurückgesetzt.</li>
                <li>Das FAAB-Budget kann Woche für Woche gespart werden. Jeder Maneger kann selbst entscheiden ob und wie viel er bieten möchte.</li>
                <li>Es ist möglich, einen Betrag von 0$ zu bieten.</li>
             </ol>
		<li>Das FAAB-Bidding wird zur Season 2023 eingeführt. Jedes Jahr ist darüber eine Abstimmung möglich.</li>
    </ol>
   
   
    <h2 class="sectionHeading" bind:this={seven}>Artikel VII: TRADES</h2>
    
    <h3 bind:this={sevenOne}>Regeln</h3>
    <ol>
         <li>Jeder Manager kann jederzeit eine beliebige Anzahl von Trades mit einer beliebigen Anzahl anderer Manager durchführen, vorausgesetzt, dass die Trades nicht unfair oder illegal sind. Vorgeschlagene Trades werden keiner Überprüfung durch die Manager unterzogen und werden nach der Annahme direkt durchgeführt.</li>
         <li>Der Commissioner ist befugt, alle Transaktionen gemäß Artikel II Abschnitt 2 Absatz e) unter den folgenden Bedingungen zu bewerten:</li>
            <ol type="a">
                <li>der Commissioner kann ein Veto gegen Transaktionen einlegen oder sie für nichtig erklären, die gegen diese Constitution verstoßen oder die nach seinem Ermessen unfair oder illegal wären;</li>
 		<li>Ebenso können alle Manager ein Veto gegen den Trade einlegen;</li>
                <li>alle derartigen Vetos müssen innerhalb von 24 Stunden nach dem Trade angekündigt werden;</li>
                <li>alle diese Vetos sind überprüfbare Entscheidungen gemäß Artikel II, Abschnitt 5; und</li>
                <li>der Commissioner muss diese Handlung mit allen Betroffenen abstimmen;</li>
            </ol>
    </ol>
    
    <h3 bind:this={sevenTwo}>Verbotene Trades</h3>
    <ol start="3">
         <li>Draft-Picks sind nicht übertragbar und dürfen nicht Teil eines Trades sein.</li>
         <li>Mit Ausnahme der Roster- und FAAB-Anforderungen gibt es keine Einschränkungen in Bezug auf die Anzahl der Spieler, die Teil eines Trades sein können.</li>
    </ol>
    
    <h3 bind:this={sevenThree}>Trade Deadline</h3>
    <ol start="5">
         <li>Die Frist für Trades ist der Anpfiff des Monday Night Spiels in Week 13.</li>
    </ol>

    <h3 bind:this={sevenFour}>FAAB-Einsatz</h3>
    <ol start="6">
         <li>Es ist möglich, das FAAB-Budget einzusetzten. Jedoch werden Trades, die das Budget sprengen, automatisch annuliert.</li>
    </ol>

    
    <h2 class="sectionHeading" bind:this={eight}>Artikel VIII: PLAYOFFS</h2> 
    
    <h3 bind:this={eightOne}>Zeit</h3>
    <ol>
         <li>Die Playoffs beginnen in Week 15 der Regular Season der NFL.</li>
         <li>Es gibt drei (3) Playoff-Runden</li>
         <li>Jede Playoff-Runde dauert eine (1) Woche.</li>
    </ol>
    
    <h3 bind:this={eightTwo}>Teilnahme</h3>
    <ol start="4">
         <li>Die sechs (6) Clubs mit der höchsten Siegquote am letzten Tag vor Beginn der Playoffs qualifizieren sich für die Playoffs.</li>
         <li>Die beiden (2) Clubs mit der höchsten Gewinnquote erhalten in der ersten Runde der Playoffs eine Bye Week.</li>
    </ol>
    
    <h3 bind:this={eightThree}>Tiebreaker</h3>
    <ol start="6">
         <li>Für den Fall, dass ein Club in Bezug auf die Win Percentage gleichauf liegen sollte, ist der Tiebreaker die Gesamtpunktzahl der erzielten Punkte (PF) während der regulären Saison.</li>
    </ol>    
    
    <h3 bind:this={eightFour}>Bestimmungen</h3>
    <ol start="7">
         <li>Der Sieger der Playoffs und damit der Liga erhält den Pokal mit eingraviertem Namen.</li>
         <li>Der Verlierer der Liga erhält einen Toiletten-Pokal.</li>
         <li>Der 7. Platz in der Consolidation Bracket (Loser Round) erhält automatisch den First Pick im Draft des folgenden Jahres. Der Sieger der Liga (1. Platz) erhält automatisch den Last Pick im Draft des folgenden Jahres.</li>
    </ol>    
    
    
    <h2 class="sectionHeading" bind:this={nine}>Artikel IX: REGELVERSTÖßE</h2> 
    
    <h3 bind:this={nineOne}>Art der Straftaten</h3>
    <ol>
         <li>Dieser Artikel befasst sich mit Regelverstößen, die über geringfügige Verstöße gegen diese Constitution hinausgehen und einer strengeren Bestrafung bedürfen.</li>
    </ol>
    
    <h3 bind:this={nineTwo}>Einleitung eines Ordnungswidrigkeitenverfahrens</h3>
    <ol start="2">
         <li>Der Commissioner kann von sich aus oder nach Eingang einer anonymen oder öffentlichen, begründeten Beschwerde verkünden, dass ein Manager eine Regelwidrigkeit begangen hat und die Strafe benennen.</li>
         <li>Der Commissioner ist befugt, mutmaßliche Regelwidrigkeiten zu untersuchen, wenn er dies für notwendig hält, und die Manager sind verpflichtet, bei solchen Untersuchungen zu helfen, indem sie dem Commissioner wahrheitsgemäße Aussagen machen, wenn sie dazu aufgefordert werden.</li>
    </ol>
    
    <h3 bind:this={nineThree}>Regelverstöße</h3>
    <ol start="4">
         <li>Jeder begeht einen Regelverstoß, der ...:</li>
            <ol type="a">
                <li>><u>Bestechung:</u> ... einer anderen Partei einen anderen Wert als den In-Game Wert im Austausch für Leistungen oder Trades im Spiel bietet.</li>
                <li>><u>Collusion:</u> ... mit einer anderen Partei vereinbart, den offenen Wettbewerb im Spiel einzuschränken, indem andere getäuscht, irregeführt oder betrogen werden, damit eine Partei, die an der Absprache beteiligt sein kann oder nicht, einen unfairen Marktvorteil erlangt.</li>
                    <ol type="i">
                        <li>Eine Collusion wird in jedem Fall angenommen, wenn ein Manager gleichzeitig für mehr als einen Club tätig ist.</li>
                    </ol>
                <li>><u>Respektlosigkeit:</u> ... beleidigende, aggressive, unangenehme oder abfällige Kommentare zu einer anderen Partei macht, die von anderen Menschen als mehr als freundlichem "Trash Talk" betrachtet werden würde.</li>
                <li>><u>Belästigung:</u> ... wiederholt eine andere Partei kontaktiert, obwohl diese Partei darum gebeten hat, dies zu unterlassen.</li>
                <li>><u>Wettbewerbswidriges Verhalten:</u> ... die Absicht zeigt, nicht mehr am Spiel teilzunehmen.</li>
                    <ol type="i">
                        <li>Unter extremen Umständen kann eine wiederholte Weigerung, sich an angemessenen Trades zu beteiligen, als wettbewerbswidriges Verhalten angesehen werden.</li>
                    </ol>
                <li>><u>Belästigung:</u> ... sich wiederholt über den Betrieb in der Liga in dem Maße beschwert, dass es auf eine Belästigung des Commissioners hinausläuft oder den Spaß anderer deutlich verringert.</li>
                <li>><u>Allgemein:</u> ... ein Verhalten zeigt, das nicht anderweitig durch diese Verfassung verboten ist, aber allgemein als beschissen anerkannt wird.</li>
            </ol>
    </ol>    
    
    <h3 bind:this={nineFour}>Strafen</h3>
    <ol start="5">
         <li>Jeder Manager, der einer Regelwidrigkeit für schuldig befunden wird, kann eine Strafe gemäß Artikel II, Abschnitt 6, einschließlich einer dauerhaften Suspendierung ohne Rücknahme erhalten.</li>
         <li>Der Commissioner kann nach eigenem Ermessen einen Club für die Handlungen eines Managers bestrafen.</li>
         <li>Entscheidungen über eine Straftat und ihre Strafe können gemäß Artikel II, Abschnitt 5 überprüft werden.</li>
         <li>Folgende Strafen werden ausgesprochen:</li>
             <ol type="a">
                 <li><b>Illegal Lineup</b> – Abzug von 10 Punkten pro illegalem Spieler. Dazu zählen aufgestellte Spieler mit folgendem Status:</li>
                        <ol type="i">
                            <li>OUT, IR, SUP, PUP;</li>
                            <li>Bye-Week; </li>
                            <li>NFL-Free Agents</li>
                        </ol>
                 <li><b>Ungültiger Spieler auf IR</b> – Abzug der Durchschnittspunkte des Spielers/der Spieler über die Saison für diesen Spieltag.</li>
                 <li>Weitere Strafen können vom Commissioner im League Chat kommuniziert werden. Insbesondere bei Wiederholten Strafen können diese vom Commissioner angepasst und verschärft werden.</li>
        </ol>
    </ol>
    
    <h3 bind:this={nineFive}>Schiedsrichter</h3>
    <ol start="9">
         <li>Der Commissioner ist nach Artikel II, Abschnitt 2, Absatz d) ausdrücklich befugt, einen neutralen Schiedsrichter zu ernennen, wenn er dies für erforderlich hält; und muss dies tun, wenn er an einem mutmaßlichen Regelverstoß selbst beteiligt ist. Trotz Artikel II, Abschnitt 5 ist die Entscheidung, einen Schiedsrichter zu ernennen, nicht diskutierbar.</li>
         <li>Ein Schiedsrichterbeschluss ist nicht bindend, sondern nur beratend.</li>
         <li>Schiedsrichterbeschlüsse dürfen nicht geheim sein.</li>
         <li>Es gibt kein Mindestquorum- oder Abstimmpflicht für eine unverbindliche Schiedsrichterabstimmung mit den Managern.</li>
    </ol>             
                 
               
 
 <p>VEREINBART mit diesem Tag, dem 23. September 2022.</p>               

    
  <h2 class="sectionHeading" bind:this={ten}>Anhang "A": FINANZEN</h2>  
   <p>Der Schatzmeister wird von der Mitgliedern der League auf unbestimmte Zeit gewählt. es ist möglich ein Misstrauensvotum zu jeder Zeit durchzuführen und gleichzeitig einen neuen Schatzmeister zu wählen. Dazu bedarf es einen formlosen Antrag an den Commissioner. Bö wurde am 15.05.2023 zum Schatzmesiter gewählt. 
   Die Aufgaben sind das Eintreiben des jährlichen Beitrags, die Verwaltung und Buchführung der Finanzen, die Genehmigung von Ausgaben und das Auszahlen des benötigten Betrags. Jedes Jahr wird von jedem Manager ein Buy-In Beitrag von 5€ erhoben. Dieses Budget soll für die Gravierung der beiden Trophäen, für eine eventuelle Neuanschaffung dieser und für den Versand an Manager dienen. Schatzmeister sammelt das Geld in der Offseason ein und verwalten es über die gesamte Zeit. Zusätzlich wird jährlch ein schriftlicher Bericht angefertigt.</p>

<table border="1">
  <tr>
    <th>Manager</th>
    <th>2023</th>
  </tr>
  <tr>
    <td>Marcus</td>
    <td></td>
  </tr>
  <tr>
    <td>Chris</td>
    <td></td>
  </tr>
    <tr>
    <td>Hembes</td>
    <td></td>
  </tr>
    <tr>
    <td>Maggi</td>
    <td></td>
  </tr>
    <tr>
    <td>Bö</td>
    <td></td>
  </tr>
    <tr>
    <td>Ecki</td>
    <td></td>
  </tr>
    <tr>
    <td>David M.</td>
    <td></td>
  </tr>
    <tr>
    <td>David S.</td>
    <td></td>
  </tr>
    <tr>
    <td>Nico</td>
    <td></td>
  </tr>
    <tr>
    <td>Marten</td>
    <td></td>
  </tr>
    <tr>
    <td>Janosch</td>
    <td></td>
  </tr>
    <tr>
    <td>Manu</td>
    <td></td>
  </tr>
</table>


  <h2 id="eins" class="sectionHeading" bind:this={eleven}>Anhang "B": VERSIONSHISTORIE</h2>  
  
  <table border="1">
  <tr>
    <th>Anhang</th>
    <th>Anhang Beschreibung</th>
    <th>Verantwortlicher</th>
    <th>Datum</th>
  </tr>
  <tr>
    <td>01</td>
    <td>Erstmalige Erstellung</td>
    <td>Marcus</td>
    <td>07.09.2019</td>
  </tr>
  <tr>
    <td>02</td>
    <td>Komplette Neuausrichtung mit Ergänzungen</td>
    <td>Marcus</td>
    <td>14.01.2022</td>
  </tr>
  <tr>
    <td>03</td>
    <td>Überarbeitung</td>
    <td>Marcus/Chris</td>
    <td>23.09.2022</td>
  </tr>
  <tr>
    <td>04</td>
    <td>Überarbeitung der Strafen</td>
    <td>Marcus</td>
    <td>06.12.2022</td>
  </tr>
  <tr>
    <td>05</td>
    <td>Überarbeitung der Constitution (FAAB, League-Median, Finanzen)</td>
    <td>Marcus</td>
    <td>04.04.2023</td>
  </tr>
</table>
    
</div>
