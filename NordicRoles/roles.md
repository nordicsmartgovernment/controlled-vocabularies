@prefix skos: <http://www.w3.org/2004/02/skos/core#> .
@prefix ex: <http://example.org/vocab#> .

ex:NordicRoles a skos:ConceptScheme ;
    dct:title "Nordic Role Vocabulary"@en ;
    dct:description "Test version of the Nordic role vocabulary based on board- and company-related roles across Sweden, Norway, Finland, and Iceland."@en ;
    skos:prefLabel "Nordic Roles (Test Version)"@en ;
    skos:note "This is a test version and may change."@en .

skos:hasTopConcept 
        ex:MemberOfTheBoard,
        ex:ChairmanOfTheBoard,
        ex:DeputyMemberOfTheBoard,
        ex:BoardObserver,
        ex:ManagingDirector,
        ex:DeputyManagingDirector,
        ex:ExternalSignatory,
        ex:SoleTrader,
        ex:ProcurationHolder,
        ex:Partner,
        ex:LimitedPartner,
        ex:OwnerMunicipality,
        ex:ManagingShipowner,
        ex:DesignatedRepresentative,
        ex:GeneralPartner,
        ex:Liquidator,
        ex:DeputyLiquidator,
        ex:BusinessManager,
        ex:ContactPerson,
        ex:Auditor,
        ex:DeputyAuditor,
        ex:Accountant,
        ex:Actuary


##########################
# Overordnede engelske begreper
##########################

ex:MemberOfTheBoard a skos:Concept ;
    skos:prefLabel "Member of the board"@en .

ex:ChairmanOfTheBoard a skos:Concept ;
    skos:prefLabel "Chairman of the board"@en .

ex:DeputyMemberOfTheBoard a skos:Concept ;
    skos:prefLabel "Deputy member of the board"@en .

ex:BoardObserver a skos:Concept ;
    skos:prefLabel "Board observer"@en .

ex:ManagingDirector a skos:Concept ;
    skos:prefLabel "Managing director"@en .

ex:DeputyManagingDirector a skos:Concept ;
    skos:prefLabel "Deputy managing director"@en .

ex:ExternalSignatory a skos:Concept ;
    skos:prefLabel "External Signatory"@en .

ex:SoleTrader a skos:Concept ;
    skos:prefLabel "Owner / Sole trader"@en .

ex:ProcurationHolder a skos:Concept ;
    skos:prefLabel "Procuration holder"@en .

ex:Partner a skos:Concept ;
    skos:prefLabel "Partner"@en .

ex:LimitedPartner a skos:Concept ;
    skos:prefLabel "Limited partner"@en .

ex:OwnerMunicipality a skos:Concept ;
    skos:prefLabel "Owner municipality"@en .

ex:ManagingShipowner a skos:Concept ;
    skos:prefLabel "Managing shipowner"@en .

ex:DesignatedRepresentative a skos:Concept ;
    skos:prefLabel "Designated Representative"@en .

ex:GeneralPartner a skos:Concept ;
    skos:prefLabel "General Partner"@en .

ex:Liquidator a skos:Concept ;
    skos:prefLabel "Liquidator"@en .

ex:DeputyLiquidator a skos:Concept ;
    skos:prefLabel "Deputy Liquidator"@en .

ex:BusinessManager a skos:Concept ;
    skos:prefLabel "Business Manager"@en .

ex:ContactPerson a skos:Concept ;
    skos:prefLabel "Contact person"@en .

ex:PersonAuthorizedToReceiveService a skos:Concept ;
    skos:prefLabel "Person authorised to receive service of process on behalf of the company"@en .

ex:Auditor a skos:Concept ;
    skos:prefLabel "Auditor"@en .

ex:DeputyAuditor a skos:Concept ;
    skos:prefLabel "Deputy Auditor"@en .

ex:Accountant a skos:Concept ;
    skos:prefLabel "Accountant"@en .

ex:Actuary a skos:Concept ;
    skos:prefLabel "Actuary"@en .

##########################
# Nordiske begreper med kobling til overordnet
##########################

# Member of the board
ex:SE_LE a skos:Concept ;
    skos:prefLabel "Styrelseledamot"@sv ;
    skos:broader ex:MemberOfTheBoard ;
    skos:notation "SE_LE" .

ex:SE_VLE a skos:Concept ;
    skos:prefLabel "Verkställande ledamot"@sv ;
    skos:broader ex:MemberOfTheBoard ;
    skos:notation "SE_VLE" .

ex:SE_ARB a skos:Concept ;
    skos:prefLabel "Arbetstagarrepresentant"@sv ;
    skos:definition "Is in the board with the same rights as other board members."@en ;
    skos:broader ex:MemberOfTheBoard ;
    skos:notation "SE_ARB" .

ex:SE_FTR a skos:Concept ;
    skos:prefLabel "Försäkringstagarrepresentant"@sv ;
    skos:definition "Is in the board with the same rights as other board members."@en ;
    skos:broader ex:MemberOfTheBoard ;
    skos:notation "SE_FTR" .

ex:FI_J a skos:Concept ;
    skos:prefLabel "Hallituksen jäsen"@fi ;
    skos:broader ex:MemberOfTheBoard ;
    skos:notation "FI_J" .

ex:NO_MEDL a skos:Concept ;
    skos:prefLabel "Styremedlem"@no ;
    skos:broader ex:MemberOfTheBoard ;
    skos:notation "NO_MEDL" .

ex:IS_12 a skos:Concept ;
    skos:prefLabel "Stjórnarmaður"@is ;
    skos:broader ex:MemberOfTheBoard ;
    skos:notation "IS_12" .

ex:IS_13 a skos:Concept ;
    skos:prefLabel "Meðstjórnandi"@is ;
    skos:broader ex:MemberOfTheBoard ;
    skos:notation "IS_13" .

# Chairman of the board
ex:SE_OF a skos:Concept ;
    skos:prefLabel "Styrelseordförande"@sv ;
    skos:definition "This person is always registered in Sweden as LE, OF and signatory rights always connected to LE."@en ;
    skos:broader ex:ChairmanOfTheBoard ;
    skos:notation "SE_OF" .

ex:SE_VOF a skos:Concept ;
    skos:prefLabel "Vice styrelseordförande"@sv ;
    skos:definition "Actually Deputy Chairman of the board but can be under this group?"@en ;
    skos:broader ex:ChairmanOfTheBoard ;
    skos:notation "SE_VOF" .

ex:FI_PJ a skos:Concept ;
    skos:prefLabel "Hallituksen puheenjohtaja"@fi ;
    skos:broader ex:ChairmanOfTheBoard ;
    skos:notation "FI_PJ" .

ex:NO_LEDE a skos:Concept ;
    skos:prefLabel "Styrets leder"@no ;
    skos:broader ex:ChairmanOfTheBoard ;
    skos:notation "NO_LEDE" .

ex:IS_11 a skos:Concept ;
    skos:prefLabel "Stjórnarformaður"@is ;
    skos:broader ex:ChairmanOfTheBoard ;
    skos:notation "IS_11" .

ex:NO_NEST a skos:Concept ;
    skos:prefLabel "Nestleder"@no ;
    skos:broader ex:ChairmanOfTheBoard ;
    skos:notation "NO_NEST" .

# Deputy member of the board
ex:SE_SU a skos:Concept ;
    skos:prefLabel "Styrelsesuppleant"@sv ;
    skos:broader ex:DeputyMemberOfTheBoard ;
    skos:notation "SE_SU" .

ex:FI_VJ a skos:Concept ;
    skos:prefLabel "Hallituksen varajäsen"@fi ;
    skos:broader ex:DeputyMemberOfTheBoard ;
    skos:notation "FI_VJ" .

ex:NO_VARA a skos:Concept ;
    skos:prefLabel "Varamedlem"@no ;
    skos:broader ex:DeputyMemberOfTheBoard ;
    skos:notation "NO_VARA" .

ex:IS_14 a skos:Concept ;
    skos:prefLabel "Varamaður"@is ;
    skos:broader ex:DeputyMemberOfTheBoard ;
    skos:notation "IS_14" .

# Board observer
ex:NO_OBS a skos:Concept ;
    skos:prefLabel "Observatør"@no ;
    skos:definition "Natural person who participates in a board meeting in a business, but without voting rights."@en ;
    skos:broader ex:BoardObserver ;
    skos:notation "NO_OBS" .

# Managing director
ex:SE_VD a skos:Concept ;
    skos:prefLabel "Verkställande direktör"@sv ;
    skos:broader ex:ManagingDirector ;
    skos:notation "SE_VD" .

ex:SE_EVD a skos:Concept ;
    skos:prefLabel "(Extern) Verkställande direktör"@sv ;
    skos:broader ex:ManagingDirector ;
    skos:notation "SE_EVD" .

ex:FI_TJ a skos:Concept ;
    skos:prefLabel "Toimitusjohtaja"@fi ;
    skos:broader ex:ManagingDirector ;
    skos:notation "FI_TJ" .

ex:NO_DAGL a skos:Concept ;
    skos:prefLabel "Daglig leder"@no ;
    skos:broader ex:ManagingDirector ;
    skos:notation "NO_DAGL" .

ex:IS_4 a skos:Concept ;
    skos:prefLabel "Framkvæmdarstjóri"@is ;
    skos:broader ex:ManagingDirector ;
    skos:notation "IS_4" .

# Deputy managing director
ex:SE_VVD a skos:Concept ;
    skos:prefLabel "Vice verkställande direktör"@sv ;
    skos:broader ex:DeputyManagingDirector ;
    skos:notation "SE_VVD" .

ex:SE_EVVD a skos:Concept ;
    skos:prefLabel "(Extern) Vice verkställande direktör"@sv ;
    skos:broader ex:DeputyManagingDirector ;
    skos:notation "SE_EVVD" .

ex:SE_SVD a skos:Concept ;
    skos:prefLabel "Ställföreträdande verkställande direktör"@sv ;
    skos:broader ex:DeputyManagingDirector ;
    skos:notation "SE_SVD" .

ex:FI_TJS a skos:Concept ;
    skos:prefLabel "Toimitusjohtajan sijainen"@fi ;
    skos:broader ex:DeputyManagingDirector ;
    skos:notation "FI_TJS" .

# (Fil fortsetter med alle øvrige roller som External Signatory, Sole Trader, Procuration Holder, Partner, etc.)
