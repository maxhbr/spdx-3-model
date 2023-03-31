SPDX-License-Identifier: Community-Spec-1.0

# RelationshipType

## Summary

Information about the relationship between two Elements.

## Description

Provides information about the relationship between two Elements.
For example, you can represent a relationship between two different Files,
between a Package and a File, between two Packages, or between one SPDXDocument and another SPDXDocument.

Build Profile specific RelationshipType descriptions can be found [here](https://github.com/spdx/spdx-3-build-profile/blob/main/model/relationships.md)

## Metadata

- name: RelationshipType

## Entries

- amends: TODOdescription
- ancestor: TODOdescription
- buildDependency: TODOdescription
- buildTool: TODOdescription
- contains: TODOdescription
- copy: TODOdescription
- dataFile: TODOdescription
- dependencyManifest: TODOdescription
- dependsOn: TODOdescription
- descendant: TODOdescription
- describes: TODOdescription
- devDependency: TODOdescription
- devTool: TODOdescription
- distributionArtifact: TODOdescription
- documentation: TODOdescription
- dynamicLink: TODOdescription
- example: TODOdescription
- expandedFromArchive: TODOdescription
- fileAdded: TODOdescription
- fileDeleted: TODOdescription
- fileModified: TODOdescription
- generates: TODOdescription
- metafile: TODOdescription
- optionalComponent: TODOdescription
- optionalDependency: TODOdescription
- other: TODOdescription
- packages: TODOdescription
- patch: TODOdescription
- prerequisite: TODOdescription
- providedDependency: TODOdescription
- requirementFor: TODOdescription
- runtimeDependency: TODOdescription
- specificationFor: TODOdescription
- staticLink: TODOdescription
- suppliedBy: TODOdescription
- test: TODOdescription
- testCase: TODOdescription
- testDependency: TODOdescription
- testTool: TODOdescription
- variant: TODOdescription
- buildInputOf: Input to the build instance
- buildOutputOf: Output of the build instance
- buildConfigOf: Build configuration of the build instance
- buildToolOf: Build tool used in the build instance
- buildInvokedBy: Agent that invoked the build
- buildOnBehalfOf: Person for which buildInvokedBy is acting on behalf of
- buildHostOf: Element in which the build instance runs on
- buildChildOf: Build instance that was created from another build instance

