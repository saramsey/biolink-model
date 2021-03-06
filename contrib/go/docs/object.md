# Slot: object


connects an association to the object of the association. For example, in a gene-to-phenotype association, the gene is subject and phenotype is object.

URI: [http://w3id.org/biolink/vocab/object](slot_uri)
## Mappings

 * [rdf:object](http://purl.obolibrary.org/obo/rdf_object)
 * [owl:annotatedTarget](http://purl.obolibrary.org/obo/owl_annotatedTarget)
 * [oban:association_has_object](http://purl.obolibrary.org/obo/oban_association_has_object)
## Domain and Range

[Association](Association.md) -> **string**
## Inheritance

 *  is_a: [association slot](association_slot.md)
## Children

 *  child: [anatomical entity to anatomical entity association.object](anatomical_entity_to_anatomical_entity_association_object.md)
 *  child: [chemical to disease or phenotypic feature association.object](chemical_to_disease_or_phenotypic_feature_association_object.md)
 *  child: [chemical to gene association.object](chemical_to_gene_association_object.md)
 *  child: [chemical to pathway association.object](chemical_to_pathway_association_object.md)
 *  child: [disease or phenotypic feature association to location association.object](disease_or_phenotypic_feature_association_to_location_association_object.md)
 *  child: [entity to disease association.object](entity_to_disease_association_object.md)
 *  child: [entity to phenotypic feature association.object](entity_to_phenotypic_feature_association_object.md)
 *  child: [functional association.object](functional_association_object.md)
 *  child: [gene regulatory relationship.object](gene_regulatory_relationship_object.md)
 *  child: [gene to expression site association.object](gene_to_expression_site_association_object.md)
 *  child: [gene to gene association.object](gene_to_gene_association_object.md)
 *  child: [genomic sequence localization.object](genomic_sequence_localization_object.md)
 *  child: [genotype to gene association.object](genotype_to_gene_association_object.md)
 *  child: [genotype to genotype part association.object](genotype_to_genotype_part_association_object.md)
 *  child: [genotype to variant association.object](genotype_to_variant_association_object.md)
 *  child: [molecular activity to biological process association.object](molecular_activity_to_biological_process_association_object.md)
 *  child: [molecular activity to downstream molecular activity association.object](molecular_activity_to_downstream_molecular_activity_association_object.md)
 *  child: [molecular activity to gene product association.object](molecular_activity_to_gene_product_association_object.md)
 *  child: [molecular activity to location association.object](molecular_activity_to_location_association_object.md)
 *  child: [pairwise interaction association.object](pairwise_interaction_association_object.md)
 *  child: [population to population association.object](population_to_population_association_object.md)
 *  child: [sequence feature relationship.object](sequence_feature_relationship_object.md)
 *  child: [sequence variant modulates treatment association.object](sequence_variant_modulates_treatment_association_object.md)
 *  child: [thing to disease or phenotypic feature association.object](thing_to_disease_or_phenotypic_feature_association_object.md)
 *  child: [variant to disease association.object](variant_to_disease_association_object.md)
 *  child: [variant to population association.object](variant_to_population_association_object.md)
## Used in

 *  usage: [AnatomicalEntityToAnatomicalEntityAssociation](AnatomicalEntityToAnatomicalEntityAssociation.md)
 *  usage: [AnatomicalEntityToAnatomicalEntityOntogenicAssociation](AnatomicalEntityToAnatomicalEntityOntogenicAssociation.md)
 *  usage: [AnatomicalEntityToAnatomicalEntityPartOfAssociation](AnatomicalEntityToAnatomicalEntityPartOfAssociation.md)
 *  usage: [Association](Association.md)
 *  usage: [BiosampleToDiseaseOrPhenotypicFeatureAssociation](BiosampleToDiseaseOrPhenotypicFeatureAssociation.md)
 *  usage: [CaseToPhenotypicFeatureAssociation](CaseToPhenotypicFeatureAssociation.md)
 *  usage: [ChemicalToDiseaseOrPhenotypicFeatureAssociation](ChemicalToDiseaseOrPhenotypicFeatureAssociation.md)
 *  usage: [ChemicalToGeneAssociation](ChemicalToGeneAssociation.md)
 *  usage: [ChemicalToPathwayAssociation](ChemicalToPathwayAssociation.md)
 *  usage: [DiseaseOrPhenotypicFeatureAssociationToLocationAssociation](DiseaseOrPhenotypicFeatureAssociationToLocationAssociation.md)
 *  usage: [DiseaseToPhenotypicFeatureAssociation](DiseaseToPhenotypicFeatureAssociation.md)
 *  usage: [EntityToDiseaseAssociation](EntityToDiseaseAssociation.md)
 *  usage: [EntityToPhenotypicFeatureAssociation](EntityToPhenotypicFeatureAssociation.md)
 *  usage: [EnvironmentToPhenotypicFeatureAssociation](EnvironmentToPhenotypicFeatureAssociation.md)
 *  usage: [ExonToTranscriptRelationship](ExonToTranscriptRelationship.md)
 *  usage: [FunctionalAssociation](FunctionalAssociation.md)
 *  usage: [GeneAsAModelOfDiseaseAssociation](GeneAsAModelOfDiseaseAssociation.md)
 *  usage: [GeneHasVariantThatContributesToDiseaseAssociation](GeneHasVariantThatContributesToDiseaseAssociation.md)
 *  usage: [GeneRegulatoryRelationship](GeneRegulatoryRelationship.md)
 *  usage: [GeneToDiseaseAssociation](GeneToDiseaseAssociation.md)
 *  usage: [GeneToExpressionSiteAssociation](GeneToExpressionSiteAssociation.md)
 *  usage: [GeneToGeneAssociation](GeneToGeneAssociation.md)
 *  usage: [GeneToGeneHomologyAssociation](GeneToGeneHomologyAssociation.md)
 *  usage: [GeneToGeneProductRelationship](GeneToGeneProductRelationship.md)
 *  usage: [GeneToGoTermAssociation](GeneToGoTermAssociation.md)
 *  usage: [GeneToPhenotypicFeatureAssociation](GeneToPhenotypicFeatureAssociation.md)
 *  usage: [GenomicSequenceLocalization](GenomicSequenceLocalization.md)
 *  usage: [GenotypeToGeneAssociation](GenotypeToGeneAssociation.md)
 *  usage: [GenotypeToGenotypePartAssociation](GenotypeToGenotypePartAssociation.md)
 *  usage: [GenotypeToPhenotypicFeatureAssociation](GenotypeToPhenotypicFeatureAssociation.md)
 *  usage: [GenotypeToVariantAssociation](GenotypeToVariantAssociation.md)
 *  usage: [MacromolecularMachineToBiologicalProcessAssociation](MacromolecularMachineToBiologicalProcessAssociation.md)
 *  usage: [MacromolecularMachineToCellularComponentAssociation](MacromolecularMachineToCellularComponentAssociation.md)
 *  usage: [MacromolecularMachineToMolecularActivityAssociation](MacromolecularMachineToMolecularActivityAssociation.md)
 *  usage: [MolecularActivityToBiologicalProcessAssociation](MolecularActivityToBiologicalProcessAssociation.md)
 *  usage: [MolecularActivityToDownstreamMolecularActivityAssociation](MolecularActivityToDownstreamMolecularActivityAssociation.md)
 *  usage: [MolecularActivityToGeneProductAssociation](MolecularActivityToGeneProductAssociation.md)
 *  usage: [MolecularActivityToLocationAssociation](MolecularActivityToLocationAssociation.md)
 *  usage: [PairwiseGeneToGeneInteraction](PairwiseGeneToGeneInteraction.md)
 *  usage: [PairwiseInteractionAssociation](PairwiseInteractionAssociation.md)
 *  usage: [PopulationToPopulationAssociation](PopulationToPopulationAssociation.md)
 *  usage: [SequenceFeatureRelationship](SequenceFeatureRelationship.md)
 *  usage: [SequenceVariantModulatesTreatmentAssociation](SequenceVariantModulatesTreatmentAssociation.md)
 *  usage: [ThingToDiseaseOrPhenotypicFeatureAssociation](ThingToDiseaseOrPhenotypicFeatureAssociation.md)
 *  usage: [TranscriptToGeneRelationship](TranscriptToGeneRelationship.md)
 *  usage: [VariantToDiseaseAssociation](VariantToDiseaseAssociation.md)
 *  usage: [VariantToPhenotypicFeatureAssociation](VariantToPhenotypicFeatureAssociation.md)
 *  usage: [VariantToPopulationAssociation](VariantToPopulationAssociation.md)
