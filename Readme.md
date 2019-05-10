# Ting vi testes på

- Implementere alle felt og aksessor og mutator metoder
- Gode navn på klasser, felt og metoder
- God bruk av javadoc på **ALLE** metoder og klasser
- Sette felt som aldri skal endres til **Final**
- Sjekke verdier/områdebegrensninger til felt
- Forklare hvorfor velger å gjøre som jeg gjør og hvordan det gjøres der det blir spurt om

## JavaDoc

- Finne riktig metode
- Riktigsvar på spm. Kan være lurespørsmål
- Sjekk i arvtreet hvor classer arver fra. Alle klasser arver hvertfall fra java.lang.Object
- Implements - bare å kopiere fra javaDoc
- Skrive hva som vil skje dersom en metode ikke fullfører
- Hva er retur verdiene

## Hovedoppgave

- Følge kravspec og holde seg til den
- Følge prinsipper for coupling, coheison og responsebility driven design
- Fornuftig og god samhandling med sluttbruker
- Oppgi alltid **enheter** på mål
- Bruke riktig løkke. Helst while med iterator
- Bruke av add-metode for å legge til i liste
- getIterator vs. implement iterator. Best å implementere interfacet 
- Lage hjelpemetoder. High cohesion
- Sjekke at vi aldri deler på 0/null
- Gi beskjed til brukeren når noe har gått galt og når noe har gått som det skal
- Ikke bruke toString i utskrift av registeret

## Arv

- Lage abstract klasse
- Implementere alle klasser

## Exception

- Excpetions skal ikke brukes til å replace if setningen, men brukes som et hjelpemiddel i checkene
- Når man lager nye exceptions må man tenkte gjennom om det skal værechecked eller unchecked. Kommenter i klassen hvorfor den er det ene eller andre

## Tester

- Lage tester
- Teste alle verdier i konstruktøren
- Lage negative tester