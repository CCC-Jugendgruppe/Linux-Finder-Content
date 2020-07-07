# Linux-Finder-Content
`
{
    "questions" : ["Wie viel Erfahrung hast du  mit Windows?", "Wie viel RAM hat dein PC?","noch eine Tolle Frage"],
    "answers" : {
        "0" : ["Erste Antwort","Zweite Antwort1", "das ist Frage 3_1", "Das ist Frage 5 oder doch4?", "erfahrung" ,"radio", 4],
        "1" : ["Erste Antwort","Zweite Antwort1", "das ist Frage 3", "Das ist Frage 5 oder doch4?","shell" ,"radio", 4],
        "2" : ["Erste Antwort","Zweite Antwort1", "das ist Frage 3", "Das ist Frage 5 oder doch4?","erfahrung" ,"radio", 4]
      	"3" : ["Testantwort", wertigkeit ,"Kategorie",  "Abfragetyp", 4]
    }
}
`

# Kategorien:
Allgemein:
Vorheriges OS
PC Anforderungen

 # Einsteiger:
 Mit Konsole vertraut
 Office
 Allgemeine Erfahrung
 Multimedia
    
  # Fortgeschritten:
 Pentesting (hacking)
    
  # Einsatzzweck:
 Gaming
 Entwicklung
 kreatives Arbeiten
 Office
 Surfen

# Oberflächen:

Einrichtbarkeit
Wichtigkeit aussehen

Ob man in der Lage ist, bei Fehlern und Problemen selbstständig eine Lösung zu finden (indem man recherchiert, Foren, Ubuntuusers usw)

### Distribution: 	Beschreibung:

## Kali Linux (Finn)

Kali ist eins der Bekanntesten Hacker Linux Distributionen es bietet viele Vorinstallierte tools zum Pentesting sei es Hashcat oder John the ripper. Es ist ein System das mit geringen systemanforderungen zurecht kommt. 
                	Es kann sowohl in der Virtuellen Maschine als auch als Live oder komplette Instalation genutzt werden. Kali ist kein System für den Altag eines nicht Pentesters da man viele Sachen erstens nicht braucht und zweitens 
                	etwas umstäntlich in der Bedienung ist.

## Raspberry Pi OS (Mattis)

Raspberry Pi OS (früher Raspbian) ist das Standart Betriebssystem für Raspberrry Pi's, es wurde für ARM Prozessoren optimiert. Es gibt drei Varianten: Raspberry Pi OS ohne Oberfläche (Zugriff über SSH), eine Variante mit Desktop und den wichtigsten Programmen und eine Version mit zusätzlichen empfohlenen Programmen wie LibreOffice, Scratch uvm.


## Parrot (Finn)
                 
Parrot ist ebenfals ein Betriebsystem das für Pentester gemacht ist ebenso wie Kali. Vom Aufbau her sind sie gleich, aber Parrot benötigt imgegensatz zu Kali noch weniger an Systemanforderungen. 
                 
## EndeavourOS 	(David)

## Arch 			(David)

## *Ubuntu: Ubuntu, Xubuntu, Kubuntu, Lubuntu, Ubuntu mate 

Ubuntu ist ein schickes und beliebtes System, vorallem für Einsteiger aber auch Fortgeschrittene. Es ist sehr beliebt, da es einige Programme wie Libre Office, Firefox usw bereits mitbringt und sich einfach bedienen lässt.
Für Linux Verhältnisse benötigt es eher mehr Ressourcen, jedoch weniger als Windows.
  
## Linux Mint 		(Mattis)

Linux Mint gibt es in 3 verschiedenen Ausführungen: XFCE für ältere Rechner oder minimalistische Nutzer, KDE und Gnome. Weiteres dazu findet ihr bei Oberflächen. Es ähnelt von der Oberfläche und Bedienung Windows sehr, Windows Nutzer werden sich gut zurecht finden.
  
## Fedora 				(Mattis)

## Zorin OS 			(Mattis)

Zorin OS ist ein ressourcenschonendes System mit hübsch gestalteten XFCE Oberfläche. Es eignet sich vorallem für sehr alte Rechner, da es sehr wenig Leistung benötigt. Es sorgt dafür, dass sich gerade schwächere Rechner schneller anfühlen, beim Browsen usw. darf man trotzdem keine Wunder erwarten, jedoch kann man mit Zorin OS das meiste auf einem alten so nutzbar wie möglich
  
## Manjaro				(Konrad?)
	
## (Android x86) (Mattis)
	
opensuse/suse (Finn) Linux ist eine Linux distributionen von der Suse GmbH, es ist eine Kostenpflichtige Linux Version. 


# Oberfläche:
Gnome
Xfce
LXDE
Plasma (KDE)
Deepin
i3
Mate
Cinnamon

`
"specs" : {
		"de_q":"Wie gut ist dein rechner"
		"de_1":"uralter Toaster",			   <2gb ram
		"de_2":"älterer Office PC",			   <4gb ram
		"de_3":"Durchschnittsrechner",			8-16gb ram
		"de_4":"Gaming PC",						16-32gb ram
		"de_5":"High end PC"				   +32gb ram
},

"consoleexp" : {
		"de_q":"Bist du mit der Konsole vertraut?",
    "de_1":"Nein, ich weiß nicht was das ist.",
   	"de_2":"Nein, aber ich habe schonmal ein paar Befehle kopiert",
    "de_3":"Ja, ich habe mich gewöhnt, gelegentlich mit ihr zu arbeiten und kenne ein paar Befehle.",
    "de_4":"Ich nutze sie oft und kenne einige Befehle",
    "de_5":"Die Konsole ist mein Zuhause, ich komme bestens zurecht!"
},

"usages" : {
		"de_q":"Wie oft nutzen sie ihren rechner für...",
    "de_1":"Nie",
    "de_2":"Selten",
    "de_3":"Manchmal",
    "de_4":"Oft",
    "de_5":"Immer",
    "de_creative":"Kreatives Arbeiten?",
    "de_coding":"Entwicklung?",
    "de_office":"Textarbeit?",
    "de_gaming":"Gaming?"
    "de_browsing":"Im internet Surfen"
`
  ui template:
  ------------

  `
  "desktop environment name" : {
		"customizeable":3,
		"generalexp":3,
		"consoleexp":3,
		"win":3,
		"mac":3,
		"coding":3,
		"office":3,
		"specs":3
  `
  ## os template:
  `
  "distro name" : {
		"specs" : 3,
		"consolesxp": 3,
		"generalexp": 3,
		"setup": 3,
		"usages":{
			"creative":3,
			"gaming":3,
			"office":3,
			"browsing":3
  	  "code":3
    }
 	}
 `
 "questions"
  "answers"
  "0", "1" usw.  
    
  definition:	depends on:
  specs: 	how powerful the hardware should be
  consoleexp: 	how much knowledge you should have on using the terminal
  general:	overall gained experience with linux
  setup:	how easy it is to install and if you need to install much additional packages
  usage:	purpose
  
  3 = default value (neutral)
  higher value means more complex or higher level
  0 = lowest, 5 = highest


  
  Distribution:
 ---------------
	`
	"endeavoros" : {
		"specs" : 2,
		"consolesxp": 4,
		"generalexp": 4,
		"setup": 4,
		"usages":{
			"creative":4,
			"gaming":4,
			"office":3,
			"browsing":3
			"code":4
		}
    "guis":["xfce","i3","cinnamon","plasma","gnome","budgie","deepin"]
	}
  
  "ubuntu" : {
		"specs" : 4,
		"consolesxp": 1,
		"generalexp": 2,
		"setup": 1,
		"usages":{
			"creative":3,
			"gaming":2,
			"office":2,
			"browsing":3
  	  "code":3
    }
  }  

  "linuxmint" : {
		"specs" : 3,
		"consolesxp": 2,
		"generalexp": 3,
		"setup": 1,
		"usages":{
			"creative":3,
			"gaming":2,
			"office":3,
			"browsing":3,
  	  "code":3,
  		}
  }

  "fedora" : {
		"specs" : 3,
		"consolesxp": 2,
		"generalexp": 4,
		"setup": 3,
		"usages":{
			"creative":3,
			"gaming":1,
			"office":1,
			"browsing":1,
  	  		"code":4,
  		}
  }
	"kali" : {
		"specs" : 3,
		"consolesxp": 2,
		"generalexp": 4,
		"setup": 2,
		"usages":{
			"creative":3,
			"gaming":1,
			"office":2,
			"browsing":2,
  	  		"code":4,
  		}
  }

  	"parrot" : {
		"specs" : 3,
		"consolesxp": 2,
		"generalexp": 4,
		"setup": 2,
		"usages":{
			"creative":3,
			"gaming":1,
			"office":2,
			"browsing":2,
  	  		"code":4,
  		}
  }
  	"suse-linux" : {
		"specs" : 3,
		"consolesxp": 2,
		"generalexp": 4,
		"setup": 2,
		"usages":{
			"creative":3,
			"gaming":1,
			"office":2,
			"browsing":2,
  	  		"code":4,
  		}
  }
	"manjaro" : {
		"specs" : 3,
		"consolesxp": 2,
		"generalexp": 4,
		"setup": 2,
		"usages":{
			"creative":3,
			"gaming":1,
			"office":2,
			"browsing":2,
  	  		"code":4,
  		}
  }
	"arch" : {
		"specs" : 3,
		"consolesxp": 2,
		"generalexp": 4,
		"setup": 2,
		"usages":{
			"creative":3,
			"gaming":1,
			"office":2,
			"browsing":2,
  	  		"code":4,
  		}
  }
	"kubuntu" : {
		"specs" : 3,
		"consolesxp": 2,
		"generalexp": 4,
		"setup": 2,
		"usages":{
			"creative":3,
			"gaming":1,
			"office":2,
			"browsing":2,
  	  		"code":4,
  		}
  }
	"xubuntu" : {
		"specs" : 3,
		"consolesxp": 2,
		"generalexp": 4,
		"setup": 2,
		"usages":{
			"creative":3,
			"gaming":1,
			"office":2,
			"browsing":2,
  	  		"code":4,
  		}
  }
	"cubuntu" : {
		"specs" : 3,
		"consolesxp": 2,
		"generalexp": 4,
		"setup": 2,
		"usages":{
			"creative":3,
			"gaming":1,
			"office":2,
			"browsing":2,
  	  		"code":4,
  		}
  }
	"lubuntu" : {
		"specs" : 3,
		"consolesxp": 2,
		"generalexp": 4,
		"setup": 2,
		"usages":{
			"creative":3,
			"gaming":1,
			"office":2,
			"browsing":2,
  	  		"code":4,
  		}
  }
	"ubuntu-mate" : {
		"specs" : 3,
		"consolesxp": 2,
		"generalexp": 4,
		"setup": 2,
		"usages":{
			"creative":3,
			"gaming":1,
			"office":2,
			"browsing":2,
  	  		"code":4,
  		}
  }
	"zorin-os" : {
		"specs" : 3,
		"consolesxp": 2,
		"generalexp": 4,
		"setup": 2,
		"usages":{
			"creative":3,
			"gaming":1,
			"office":2,
			"browsing":2,
  	  		"code":4,
  		}
  }
    
	"instant-os" : {
		"specs" : 3,
		"consolesxp": 2,
		"generalexp": 4,
		"setup": 2,
		"usages":{
			"creative":3,
			"gaming":1,
			"office":2,
			"browsing":2,
  	  		"code":4,
  		}
  }
  "open-suse" : {
		"specs" : 3,
		"consolesxp": 2,
		"generalexp": 4,
		"setup": 2,
		"usages":{
			"creative":3,
			"gaming":1,
			"office":2,
			"browsing":2,
  	  "code":4,
  		}
  }

`  

  # Oberflächen:
`
	"xfce" : {
		"customizeable":5,
		"generalexp":3,
		"consoleexp":4,
		"win":4,
		"mac":2,
		"coding":4,
		"office":4,
    "browsing":4,
		"specs":2
	}
    
  "lxde" : {
		"customizeable":4,
		"generalexp":3,
		"consoleexp":4,
		"win":2,
		"mac":3,
		"coding":4,
		"office":4,
    "browsing":2,
		"specs":2
	}
    
  "gnome" : {
		"customizeable":1,
		"generalexp":2,
		"consoleexp":2,
		"win":3,
		"mac":4,
		"coding":4,
		"office":3,
    "browsing":3,
		"specs":4
	}
    
  "kde" : {
		"customizeable":2,
		"generalexp":2,
		"consoleexp":2,
		"win":3,
		"mac":4,
		"coding":4,
		"office":3,
    "browsing":3,
		"specs":2
	}
 `
   
    Linux ist ein freies Betriebssystem, wovon es anders als bei Windows oder Mac OS viele verschiedene Systeme gibt. Die meisten Linux Distributionen sind kostenlos und fühlen sich schneller an, da weniger Programme vorinstalliert sind.
    Die Verschiedenen Systeme legen ihren Fokus auf verschiedene Einsatzzwecke, man kann sich also entscheiden, welches Betriebsssystem man nutzen möchte.
    Damit ihnen die Wahl einer Linux Distibution leichter fällt,wurde dieser Linux-Finder entwickelt. Die meisten Systeme können sie selbst (über ein Live-System) ausprobieren, ohne Änderungen an ihrem rechner vorzunehmen. Wie das geht, zeigen wir ihnen h
    Das Ziel des Linux Finders ist es, für jeden das passende Linux zu finden. Hierfür müssen sie unten einfach die Fragen Beantworten. Sie müssen keine Persönlichen Daten eingeben wie zum Beispiel Name und Adresse, wir benötigen lediglich 
    die Rechnerleistung und wofür es Benötigt wird. Der Linux Finder wurde von der CCC Jugendgruppe aus Göttingen entwickelt den Code kann man sich auf Github anschauen.(https://github.com/CCC-Jugendgruppe)
  
