@prefix skos: <http://www.w3.org/2004/02/skos/core#> .
@prefix dct:  <http://purl.org/dc/terms/> .
@prefix ex:   <http://example.org/vocab#> .

############################################################
# ConceptScheme
############################################################

ex:NordicRoles a skos:ConceptScheme ;
    dct:title "Nordic Role Vocabulary"@en ;
    dct:description "Test version of the Nordic role vocabulary based on board- and company-related roles across Sweden, Norway, Finland, and Iceland."@en ;
    skos:prefLabel "Nordic Roles (Test Version)"@en ;
    skos:note "This is a test version and may change."@en .

############################################################
# Top Concepts
############################################################

ex:MemberOfTheBoard a skos:Concept ;
    skos:prefLabel "Member of the board"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:ChairmanOfTheBoard a skos:Concept ;
    skos:prefLabel "Chairman of the board"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:DeputyMemberOfTheBoard a skos:Concept ;
    skos:prefLabel "Deputy member of the board"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:BoardObserver a skos:Concept ;
    skos:prefLabel "Board observer"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:ManagingDirector a skos:Concept ;
    skos:prefLabel "Managing director"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:DeputyManagingDirector a skos:Concept ;
    skos:prefLabel "Deputy managing director"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:ExternalSignatory a skos:Concept ;
    skos:prefLabel "External signatory"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:SoleTraderOrOwner a skos:Concept ;
    skos:prefLabel "Sole trader or owner"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:ProcurationHolder a skos:Concept ;
    skos:prefLabel "Procuration holder"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:Partner a skos:Concept ;
    skos:prefLabel "Partner"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:PartnersJointSeveralLiability a skos:Concept ;
    skos:prefLabel "Partner with joint and several liability"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:PartnersProRataLiability a skos:Concept ;
    skos:prefLabel "Partner with pro rata liability"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:LimitedPartner a skos:Concept ;
    skos:prefLabel "Limited partner"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:OwnerMunicipality a skos:Concept ;
    skos:prefLabel "Owner municipality"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:ManagingShipowner a skos:Concept ;
    skos:prefLabel "Managing owner in a joint-owned shipping firm"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:DesignatedRepresentative a skos:Concept ;
    skos:prefLabel "Designated representative"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:GeneralPartner a skos:Concept ;
    skos:prefLabel "General partner"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:Liquidator a skos:Concept ;
    skos:prefLabel "Liquidator"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:DeputyLiquidator a skos:Concept ;
    skos:prefLabel "Deputy liquidator"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:BusinessManager a skos:Concept ;
    skos:prefLabel "Business manager"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:ContactPerson a skos:Concept ;
    skos:prefLabel "Contact person"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:ServiceOfProcessReceiver a skos:Concept ;
    skos:prefLabel "Service of process receiver"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:Auditor a skos:Concept ;
    skos:prefLabel "Auditor"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:DeputyAuditor a skos:Concept ;
    skos:prefLabel "Deputy auditor"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:Accountant a skos:Concept ;
    skos:prefLabel "Accountant"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

ex:Actuary a skos:Concept ;
    skos:prefLabel "Actuary"@en ;
    skos:topConceptOf ex:NordicRoles ;
    skos:inScheme ex:NordicRoles .

############################################################
# SUBCONCEPTS (ALL ROLES FROM TABLE)
############################################################

# ---- Member of the Board ----------------------------------------------------

ex:SE_LE a skos:Concept ;
    skos:broader ex:MemberOfTheBoard ;
    skos:notation "SE_LE" ;
    skos:prefLabel "Styrelseledamot"@sv ;
    skos:inScheme ex:NordicRoles .

ex:SE_VLE a skos:Concept ;
    skos:broader ex:MemberOfTheBoard ;
    skos:notation "SE_VLE" ;
    skos:prefLabel "Verkställande ledamot"@sv ;
    skos:inScheme ex:NordicRoles .

ex:SE_ARB a skos:Concept ;
    skos:broader ex:MemberOfTheBoard ;
    skos:notation "SE_ARB" ;
    skos:prefLabel "Arbetstagarrepresentant"@sv ;
    skos:note "Is in the board with the same rights as other board members."@en ;
    skos:inScheme ex:NordicRoles .

ex:SE_FTR a skos:Concept ;
    skos:broader ex:MemberOfTheBoard ;
    skos:notation "SE_FTR" ;
    skos:prefLabel "Försäkringstagarrepresentant"@sv ;
    skos:note "Is in the board with the same rights as other board members."@en ;
    skos:inScheme ex:NordicRoles .

ex:FI_J a skos:Concept ;
    skos:broader ex:MemberOfTheBoard ;
    skos:notation "FI_J" ;
    skos:prefLabel "Hallituksen jäsen"@fi ;
    skos:inScheme ex:NordicRoles .

ex:NO_MEDL a skos:Concept ;
    skos:broader ex:MemberOfTheBoard ;
    skos:notation "NO_MEDL" ;
    skos:prefLabel "Styremedlem"@nb ;
    skos:inScheme ex:NordicRoles .

ex:IS_12 a skos:Concept ;
    skos:broader ex:MemberOfTheBoard ;
    skos:notation "IS_12" ;
    skos:prefLabel "Stjórnarmaður"@is ;
    skos:inScheme ex:NordicRoles .

ex:IS_13 a skos:Concept ;
    skos:broader ex:MemberOfTheBoard ;
    skos:notation "IS_13" ;
    skos:prefLabel "Meðstjórnandi"@is ;
    skos:inScheme ex:NordicRoles .

# ---- Chairman of the Board --------------------------------------------------

ex:SE_OF a skos:Concept ;
    skos:broader ex:ChairmanOfTheBoard ;
    skos:notation "SE_OF" ;
    skos:prefLabel "Styrelseordförande"@sv ;
    skos:note "Person always registered as LE, OF, with signatory rights connected to LE."@en ;
    skos:inScheme ex:NordicRoles .

ex:SE_VOF a skos:Concept ;
    skos:broader ex:ChairmanOfTheBoard ;
    skos:notation "SE_VOF" ;
    skos:prefLabel "Vice styrelseordförande"@sv ;
    skos:note "Deputy Chairman of the Board."@en ;
    skos:inScheme ex:NordicRoles .

ex:FI_PJ a skos:Concept ;
    skos:broader ex:ChairmanOfTheBoard ;
    skos:notation "FI_PJ" ;
    skos:prefLabel "Hallituksen puheenjohtaja"@fi ;
    skos:inScheme ex:NordicRoles .

ex:NO_LEDE a skos:Concept ;
    skos:broader ex:ChairmanOfTheBoard ;
    skos:notation "NO_LEDE" ;
    skos:prefLabel "Styrets leder"@nb ;
    skos:inScheme ex:NordicRoles .

ex:IS_11 a skos:Concept ;
    skos:broader ex:ChairmanOfTheBoard ;
    skos:notation "IS_11" ;
    skos:prefLabel "Stjórnarformaður"@is ;
    skos:inScheme ex:NordicRoles .

ex:NO_NEST a skos:Concept ;
    skos:broader ex:ChairmanOfTheBoard ;
    skos:notation "NO_NEST" ;
    skos:prefLabel "Nestleder"@nb ;
    skos:inScheme ex:NordicRoles .

# ---- Deputy Member of the Board --------------------------------------------

ex:SE_SU a skos:Concept ;
    skos:broader ex:DeputyMemberOfTheBoard ;
    skos:notation "SE_SU" ;
    skos:prefLabel "Styrelsesuppleant"@sv ;
    skos:note "Does not have signatory rights unless delegated."@en ;
    skos:inScheme ex:NordicRoles .

ex:FI_VJ a skos:Concept ;
    skos:broader ex:DeputyMemberOfTheBoard ;
    skos:notation "FI_VJ" ;
    skos:prefLabel "Hallituksen varajäsen"@fi ;
    skos:inScheme ex:NordicRoles .

ex:NO_VARA a skos:Concept ;
    skos:broader ex:DeputyMemberOfTheBoard ;
    skos:notation "NO_VARA" ;
    skos:prefLabel "Varamedlem"@nb ;
    skos:inScheme ex:NordicRoles .

ex:IS_14 a skos:Concept ;
    skos:broader ex:DeputyMemberOfTheBoard ;
    skos:notation "IS_14" ;
    skos:prefLabel "Varamaður"@is ;
    skos:inScheme ex:NordicRoles .

# ---- Board Observer ---------------------------------------------------------

ex:NO_OBS a skos:Concept ;
    skos:broader ex:BoardObserver ;
    skos:notation "NO_OBS" ;
    skos:prefLabel "Observatør"@nb ;
    skos:note "Natural person participating in board meetings without voting rights."@en ;
    skos:inScheme ex:NordicRoles .

# ---- Managing Director ------------------------------------------------------

ex:SE_VD a skos:Concept ;
    skos:broader ex:ManagingDirector ;
    skos:notation "SE_VD" ;
    skos:prefLabel "Verkställande direktör"@sv ;
    skos:inScheme ex:NordicRoles .

ex:SE_EVD a skos:Concept ;
    skos:broader ex:ManagingDirector ;
    skos:notation "SE_EVD" ;
    skos:prefLabel "(Extern) Verkställande direktör"@sv ;
    skos:inScheme ex:NordicRoles .

ex:FI_TJ a skos:Concept ;
    skos:broader ex:ManagingDirector ;
    skos:notation "FI_TJ" ;
    skos:prefLabel "Toimitusjohtaja"@fi ;
    skos:inScheme ex:NordicRoles .

ex:NO_DAGL a skos:Concept ;
    skos:broader ex:ManagingDirector ;
    skos:notation "NO_DAGL" ;
    skos:prefLabel "Daglig leder"@nb ;
    skos:inScheme ex:NordicRoles .

ex:IS_4 a skos:Concept ;
    skos:broader ex:ManagingDirector ;
    skos:notation "IS_4" ;
    skos:prefLabel "Framkvæmdarstjóri"@is ;
    skos:inScheme ex:NordicRoles .

# ---- Deputy Managing Director ------------------------------------------------

ex:SE_VVD a skos:Concept ;
    skos:broader ex:DeputyManagingDirector ;
    skos:notation "SE_VVD" ;
    skos:prefLabel "Vice verkställande direktör"@sv ;
    skos:inScheme ex:NordicRoles .

ex:SE_EVVD a skos:Concept ;
    skos:broader ex:DeputyManagingDirector ;
    skos:notation "SE_EVVD" ;
    skos:prefLabel "(Extern) Vice verkställande direktör"@sv ;
    skos:inScheme ex:NordicRoles .

ex:SE_SVD a skos:Concept ;
    skos:broader ex:DeputyManagingDirector ;
    skos:notation "SE_SVD" ;
    skos:prefLabel "Ställföreträdande verkställande direktör"@sv ;
    skos:inScheme ex:NordicRoles .

ex:FI_TJS a skos:Concept ;
    skos:broader ex:DeputyManagingDirector ;
    skos:notation "FI_TJS" ;
    skos:prefLabel "Toimitusjohtajan sijainen"@fi ;
    skos:inScheme ex:NordicRoles .

# ---- External Signatory -----------------------------------------------------

ex:SE_EFT a skos:Concept ;
    skos:broader ex:ExternalSignatory ;
    skos:notation "SE_EFT" ;
    skos:prefLabel "Extern firmatecknare"@sv ;
    skos:inScheme ex:NordicRoles .

ex:FI_MUU a skos:Concept ;
    skos:broader ex:ExternalSignatory ;
    skos:notation "FI_MUU" ;
    skos:prefLabel "Muu nimetty henkilö"@fi ;
    skos:inScheme ex:NordicRoles .

ex:NO_SIGN a skos:Concept ;
    skos:broader ex:ExternalSignatory ;
    skos:notation "NO_SIGN" ;
    skos:prefLabel "Signaturberettiget"@nb ;
    skos:inScheme ex:NordicRoles .

# ---- Sole Trader / Owner ----------------------------------------------------

ex:SE_IN a skos:Concept ;
    skos:broader ex:SoleTraderOrOwner ;
    skos:notation "SE_IN" ;
    skos:prefLabel "Enskild näringsidkare"@sv ;
    skos:note "A sole trader has signatory rights in their business."@en ;
    skos:inScheme ex:NordicRoles .

ex:FI_YEH a skos:Concept ;
    skos:broader ex:SoleTraderOrOwner ;
    skos:notation "FI_YEH" ;
    skos:prefLabel "Yksityinen elinkeinonharjoittaja"@fi ;
    skos:inScheme ex:NordicRoles .

ex:NO_INNH a skos:Concept ;
    skos:broader ex:SoleTraderOrOwner ;
    skos:notation "NO_INNH" ;
    skos:prefLabel "Innehaver"@nb ;
    skos:inScheme ex:NordicRoles .

ex:IS_3 a skos:Concept ;
    skos:broader ex:SoleTraderOrOwner ;
    skos:notation "IS_3" ;
    skos:prefLabel "Eigandi"@is ;
    skos:inScheme ex:NordicRoles .

# ---- Procuration Holder ------------------------------------------------------

ex:SE_PO a skos:Concept ;
    skos:broader ex:ProcurationHolder ;
    skos:notation "SE_PO" ;
    skos:prefLabel "Prokurist"@sv ;
    skos:note "In Sweden only used for Handelsbolag."@en ;
    skos:inScheme ex:NordicRoles .

ex:FI_PR a skos:Concept ;
    skos:broader ex:ProcurationHolder ;
    skos:notation "FI_PR" ;
    skos:prefLabel "Prokuristi"@fi ;
    skos:inScheme ex:NordicRoles .

ex:IS_5 a skos:Concept ;
    skos:broader ex:ProcurationHolder ;
    skos:notation "IS_5" ;
    skos:prefLabel "Prókúruhafi"@is ;
    skos:inScheme ex:NordicRoles .

ex:NO_PROK a skos:Concept ;
    skos:broader ex:ProcurationHolder ;
    skos:notation "NO_PROK" ;
    skos:prefLabel "Prokurist"@nb ;
    skos:inScheme ex:NordicRoles .

# ---- Partner ---------------------------------------------------------------

ex:SE_BO a skos:Concept ;
    skos:broader ex:Partner ;
    skos:notation "SE_BO" ;
    skos:prefLabel "Bolagsman"@sv ;
    skos:note "Used in Handelsbolag and Kommanditbolag."@en ;
    skos:inScheme ex:NordicRoles .

ex:FI_YHM a skos:Concept ;
    skos:broader ex:Partner ;
    skos:notation "FI_YHM" ;
    skos:prefLabel "Yhtiömies"@fi ;
    skos:inScheme ex:NordicRoles .

ex:NO_DTSO a skos:Concept ;
    skos:broader ex:PartnersJointSeveralLiability ;
    skos:notation "NO_DTSO" ;
    skos:prefLabel "Deltaker med solidarisk ansvar"@nb ;
    skos:note "Unlimited liability in Norwegian companies with full liability."@en ;
    skos:inScheme ex:NordicRoles .

ex:NO_DTPR a skos:Concept ;
    skos:broader ex:PartnersProRataLiability ;
    skos:notation "NO_DTPR" ;
    skos:prefLabel "Deltaker med proratarisk ansvar"@nb ;
    skos:inScheme ex:NordicRoles .

# ---- Limited Partner -------------------------------------------------------

ex:SE_KD a skos:Concept ;
    skos:broader ex:LimitedPartner ;
    skos:notation "SE_KD" ;
    skos:prefLabel "Kommanditdelägare"@sv ;
    skos:inScheme ex:NordicRoles .

ex:FI_YHMÄ a skos:Concept ;
    skos:broader ex:LimitedPartner ;
    skos:notation "FI_YHMÄ" ;
    skos:prefLabel "Äänetön yhtiömies"@fi ;
    skos:note "Direct translation: silent partner."@en ;
    skos:inScheme ex:NordicRoles .

# ---- Owner Municipality -----------------------------------------------------

ex:NO_EIKM a skos:Concept ;
    skos:broader ex:OwnerMunicipality ;
    skos:notation "NO_EIKM" ;
    skos:prefLabel "Eierkommune"@nb ;
    skos:inScheme ex:NordicRoles .

# ---- Managing Shipowner -----------------------------------------------------

ex:NO_BEST a skos:Concept ;
    skos:broader ex:ManagingShipowner ;
    skos:notation "NO_BEST" ;
    skos:prefLabel "Bestyrende reder"@nb ;
    skos:inScheme ex:NordicRoles .

# ---- Designated Representative ---------------------------------------------

ex:SE_FO a skos:Concept ;
    skos:broader ex:DesignatedRepresentative ;
    skos:notation "SE_FO" ;
    skos:prefLabel "Föreståndare"@sv ;
    skos:note "Required for non-Swedish citizens running a sole trader business."@en ;
    skos:inScheme ex:NordicRoles .

ex:NO_REPR a skos:Concept ;
    skos:broader ex:DesignatedRepresentative ;
    skos:notation "NO_REPR" ;
    skos:prefLabel "Norsk representant for utenlandsk enhet"@nb ;
    skos:note "Required when foreign companies operate in Norway."@en ;
    skos:inScheme ex:NordicRoles .

# ---- General Partner --------------------------------------------------------

ex:SE_KP a skos:Concept ;
    skos:broader ex:GeneralPartner ;
    skos:notation "SE_KP" ;
    skos:prefLabel "Komplementär"@sv ;
    skos:inScheme ex:NordicRoles .

ex:FI_VYHM a skos:Concept ;
    skos:broader ex:GeneralPartner ;
    skos:notation "FI_VYHM" ;
    skos:prefLabel "Vastuunalainen yhtiömies"@fi ;
    skos:inScheme ex:NordicRoles .

ex:NO_KOMP a skos:Concept ;
    skos:broader ex:GeneralPartner ;
    skos:notation "NO_KOMP" ;
    skos:prefLabel "Komplementar"@nb ;
    skos:inScheme ex:NordicRoles .

# ---- Liquidator -------------------------------------------------------------

ex:SE_LI a skos:Concept ;
    skos:broader ex:Liquidator ;
    skos:notation "SE_LI" ;
    skos:prefLabel "Likvidator"@sv ;
    skos:note "Has signatory power during liquidation."@en ;
    skos:inScheme ex:NordicRoles .

ex:FI_LIQ a skos:Concept ;
    skos:broader ex:Liquidator ;
    skos:notation "FI_LIQ" ;
    skos:prefLabel "Selvitysmies"@fi ;
    skos:inScheme ex:NordicRoles .

ex:NO_BOBE a skos:Concept ;
    skos:broader ex:Liquidator ;
    skos:notation "NO_BOBE" ;
    skos:prefLabel "Bostyrer"@nb ;
    skos:note "Receiver / official receiver / trustee in bankruptcy."@en ;
    skos:inScheme ex:NordicRoles .

# ---- Deputy Liquidator ------------------------------------------------------

ex:SE_LS a skos:Concept ;
    skos:broader ex:DeputyLiquidator ;
    skos:notation "SE_LS" ;
    skos:prefLabel "Likvidatorssuppleant"@sv ;
    skos:inScheme ex:NordicRoles .

# ---- Business Manager -------------------------------------------------------

ex:NO_FFOER a skos:Concept ;
    skos:broader ex:BusinessManager ;
    skos:notation "NO_FFOER" ;
    skos:prefLabel "Forretningsfører"@nb ;
    skos:note "Handles administrative tasks. Below general manager if present."@en ;
    skos:inScheme ex:NordicRoles .

# ---- Contact Person ---------------------------------------------------------

ex:NO_KONT a skos:Concept ;
    skos:broader ex:ContactPerson ;
    skos:notation "NO_KONT" ;
    skos:prefLabel "Kontaktperson"@nb ;
    skos:inScheme ex:NordicRoles .

ex:SE_REP a skos:Concept ;
    skos:broader ex:ContactPerson ;
    skos:notation "SE_REP" ;
    skos:prefLabel "Representant"@sv ;
    skos:note "Used for religious communities, e.g., a priest."@en ;
    skos:inScheme ex:NordicRoles .

# ---- Service of Process Receiver -------------------------------------------

ex:SE_DELG a skos:Concept ;
    skos:broader ex:ServiceOfProcessReceiver ;
    skos:notation "SE_DELG" ;
    skos:prefLabel "Delgivningsmottagare"@sv ;
    skos:note "Can be similar to a contact person."@en ;
    skos:inScheme ex:NordicRoles .

# ---- Auditor ---------------------------------------------------------------

ex:NO_REVI a skos:Concept ;
    skos:broader ex:Auditor ;
    skos:notation "NO_REVI" ;
    skos:prefLabel "Revisor"@nb ;
    skos:inScheme ex:NordicRoles .

ex:SE_REV a skos:Concept ;
    skos:broader ex:Auditor ;
    skos:notation "SE_REV" ;
    skos:prefLabel "Revisor"@sv ;
    skos:inScheme ex:NordicRoles .

ex:SE_REVH a skos:Concept ;
    skos:broader ex:Auditor ;
    skos:notation "SE_REVH" ;
    skos:prefLabel "Huvudansvarig revisor"@sv ;
    skos:inScheme ex:NordicRoles .

ex:SE_REVT a skos:Concept ;
    skos:broader ex:Auditor ;
    skos:notation "SE_REVT" ;
    skos:prefLabel "Revisor (med tillstånd)"@sv ;
    skos:inScheme ex:NordicRoles .

ex:SE_REVL a skos:Concept ;
    skos:broader ex:Auditor ;
    skos:notation "SE_REVL" ;
    skos:prefLabel "Lekmannarevisor"@sv ;
    skos:note "Layman auditor."@en ;
    skos:inScheme ex:NordicRoles .

ex:IS_AUD a skos:Concept ;
    skos:broader ex:Auditor ;
    skos:notation "IS_AUD" ;
    skos:prefLabel "Skoðunarmaður"@is ;
    skos:inScheme ex:NordicRoles .

ex:FI_T a skos:Concept ;
    skos:broader ex:Auditor ;
    skos:notation "FI_T" ;
    skos:prefLabel "Tilintarkastaja"@fi ;
    skos:inScheme ex:NordicRoles .

ex:FI_PTI a skos:Concept ;
    skos:broader ex:Auditor ;
    skos:notation "FI_PTI" ;
    skos:prefLabel "Päävastuullinen tilintarkastaja"@fi ;
    skos:inScheme ex:NordicRoles .

# ---- Deputy Auditor ---------------------------------------------------------

ex:SE_REVS a skos:Concept ;
    skos:broader ex:DeputyAuditor ;
    skos:notation "SE_REVS" ;
    skos:prefLabel "Revisorssuppleant"@sv ;
    skos:inScheme ex:NordicRoles .

ex:SE_REVSL a skos:Concept ;
    skos:broader ex:DeputyAuditor ;
    skos:notation "SE_REVSL" ;
    skos:prefLabel "Suppleant för lekmannarevisor"@sv ;
    skos:inScheme ex:NordicRoles .

ex:SE_REVST a skos:Concept ;
    skos:broader ex:DeputyAuditor ;
    skos:notation "SE_REVST" ;
    skos:prefLabel "Revisorssuppleant (med tillstånd)"@sv ;
    skos:inScheme ex:NordicRoles .

ex:FI_VT a skos:Concept ;
    skos:broader ex:DeputyAuditor ;
    skos:notation "FI_VT" ;
    skos:prefLabel "Varatilintarkastaja"@fi ;
    skos:inScheme ex:NordicRoles .

# ---- Accountant -------------------------------------------------------------

ex:NO_REGN a skos:Concept ;
    skos:broader ex:Accountant ;
    skos:notation "NO_REGN" ;
    skos:prefLabel "Regnskapsfører"@nb ;
    skos:inScheme ex:NordicRoles .

ex:IS_2 a skos:Concept ;
    skos:broader ex:Accountant ;
    skos:notation "IS_2" ;
    skos:prefLabel "Endurskoðandi"@is ;
    skos:inScheme ex:NordicRoles .

# ---- Actuary ---------------------------------------------------------------

ex:SE_AK a skos:Concept ;
    skos:broader ex:Actuary ;
    skos:notation "SE_AK" ;
    skos:prefLabel "Aktuarie"@sv ;
    skos:inScheme ex:NordicRoles .


