# Recipes for AGP version `8.5`
This branch contains recipes compatible with AGP 8.5. If you want to find recipes
for other AGP versions, switch to the corresponding `agp-*` branch.

This branch is read only. Contributions are only accepted on the `studio-main` branch. See `CONTRIBUTION.md`
there.
# Recipes Index
Index is organized in categories, offering different ways to reach the recipe you want.
## Themes
* Android Assets - [addGeneratedSourceFolder](addGeneratedSourceFolder), [legacyTaskBridging](legacyTaskBridging)
* Android Manifest - [createSingleArtifact](createSingleArtifact), [transformManifest](transformManifest), [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* Artifact API - [appendToScopedArtifacts](appendToScopedArtifacts), [listenToMultipleArtifact](listenToMultipleArtifact), [getSingleArtifact](getSingleArtifact), [getMultipleArtifact](getMultipleArtifact), [getScopedArtifacts](getScopedArtifacts), [transformAllClasses](transformAllClasses), [createSingleArtifact](createSingleArtifact), [appendToMultipleArtifact](appendToMultipleArtifact), [transformMultiple](transformMultiple), [workerEnabledTransformation](workerEnabledTransformation), [addMultipleArtifact](addMultipleArtifact), [transformManifest](transformManifest), [transformDirectory](transformDirectory), [listenToArtifacts](listenToArtifacts)
* DSL - [extendingAgp](extendingAgp), [addBuildTypeUsingDslFinalize](addBuildTypeUsingDslFinalize)
* Dependency Resolution - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* Sources - [addCustomSourceType](addCustomSourceType), [addGeneratedSourceFolder](addGeneratedSourceFolder), [legacyTaskBridging](legacyTaskBridging)
## Plugin Features
* TestFixtures - [testFixtures](testFixtures)
## APIs
* AndroidComponentsExtension.beforeVariants() - [selectVariants](selectVariants)
* AndroidComponentsExtension.onVariants() - [appendToScopedArtifacts](appendToScopedArtifacts), [listenToMultipleArtifact](listenToMultipleArtifact), [extendingAgp](extendingAgp), [getSingleArtifact](getSingleArtifact), [addCustomSourceType](addCustomSourceType), [getMultipleArtifact](getMultipleArtifact), [getScopedArtifacts](getScopedArtifacts), [transformAllClasses](transformAllClasses), [variantDependencySubstitutionTest](variantDependencySubstitutionTest), [createSingleArtifact](createSingleArtifact), [appendToMultipleArtifact](appendToMultipleArtifact), [onVariants](onVariants), [addCustomBuildConfigFields](addCustomBuildConfigFields), [addGeneratedSourceFolder](addGeneratedSourceFolder), [transformMultiple](transformMultiple), [registerPreBuild](registerPreBuild), [variantOutput](variantOutput), [workerEnabledTransformation](workerEnabledTransformation), [addMultipleArtifact](addMultipleArtifact), [allProjectsApkAction](allProjectsApkAction), [legacyTaskBridging](legacyTaskBridging), [transformManifest](transformManifest), [transformDirectory](transformDirectory), [perVariantManifestPlaceholder](perVariantManifestPlaceholder), [asmTransformClasses](asmTransformClasses), [listenToArtifacts](listenToArtifacts)
* AndroidComponentsExtension.registerExtension() - [extendingAgp](extendingAgp)
* AndroidComponentsExtension.selector() - [selectVariants](selectVariants), [variantOutput](variantOutput), [allProjectsApkAction](allProjectsApkAction)
* ApplicationVariant.applicationId - [onVariants](onVariants)
* ApplicationVariant.outputs - [variantOutput](variantOutput)
* Artifact.ContainsMany - [listenToArtifacts](listenToArtifacts)
* ArtifactTransformationRequest - [workerEnabledTransformation](workerEnabledTransformation)
* Artifacts.add() - [transformMultiple](transformMultiple), [addMultipleArtifact](addMultipleArtifact)
* Artifacts.forScope() - [appendToScopedArtifacts](appendToScopedArtifacts), [getScopedArtifacts](getScopedArtifacts), [transformAllClasses](transformAllClasses)
* Artifacts.get() - [getSingleArtifact](getSingleArtifact), [appendToMultipleArtifact](appendToMultipleArtifact), [addGeneratedSourceFolder](addGeneratedSourceFolder), [transformMultiple](transformMultiple), [variantOutput](variantOutput), [addMultipleArtifact](addMultipleArtifact), [allProjectsApkAction](allProjectsApkAction), [legacyTaskBridging](legacyTaskBridging), [transformManifest](transformManifest), [transformDirectory](transformDirectory), [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* Artifacts.getAll() - [getMultipleArtifact](getMultipleArtifact)
* Artifacts.use() - [listenToMultipleArtifact](listenToMultipleArtifact), [createSingleArtifact](createSingleArtifact), [appendToMultipleArtifact](appendToMultipleArtifact), [transformMultiple](transformMultiple), [workerEnabledTransformation](workerEnabledTransformation), [transformManifest](transformManifest), [transformDirectory](transformDirectory), [listenToArtifacts](listenToArtifacts)
* BuildConfigField() - [addCustomBuildConfigFields](addCustomBuildConfigFields)
* BuiltArtifact - [workerEnabledTransformation](workerEnabledTransformation)
* BuiltArtifact.versionCode - [listenToArtifacts](listenToArtifacts)
* BuiltArtifact.versionName - [listenToArtifacts](listenToArtifacts)
* BuiltArtifacts.elements - [listenToArtifacts](listenToArtifacts)
* BuiltArtifacts.variantName - [listenToArtifacts](listenToArtifacts)
* BuiltArtifactsLoader.load() - [listenToArtifacts](listenToArtifacts)
* CanMinifyAndroidResourcesBuilder.shrinkResources - [selectVariants](selectVariants)
* CanMinifyCodeBuilder.isMinifyEnabled - [selectVariants](selectVariants)
* CombiningOperationRequest.toTransform() - [transformMultiple](transformMultiple)
* Component.artifacts - [appendToScopedArtifacts](appendToScopedArtifacts), [getMultipleArtifact](getMultipleArtifact), [getScopedArtifacts](getScopedArtifacts), [createSingleArtifact](createSingleArtifact), [appendToMultipleArtifact](appendToMultipleArtifact), [addGeneratedSourceFolder](addGeneratedSourceFolder), [transformMultiple](transformMultiple), [variantOutput](variantOutput), [addMultipleArtifact](addMultipleArtifact), [legacyTaskBridging](legacyTaskBridging), [transformManifest](transformManifest), [transformDirectory](transformDirectory)
* Component.compileConfiguration - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* Component.runtimeConfiguration - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* Component.sources - [addCustomSourceType](addCustomSourceType), [addGeneratedSourceFolder](addGeneratedSourceFolder), [legacyTaskBridging](legacyTaskBridging)
* Configuration.resolutionStrategy - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* DslExtension.Builder.build() - [extendingAgp](extendingAgp)
* DslExtension.Builder.extendBuildTypeWith() - [extendingAgp](extendingAgp)
* DslExtension.Builder.extendProductFlavorWith() - [extendingAgp](extendingAgp)
* DslExtension.Builder.extendProjectWith() - [extendingAgp](extendingAgp)
* DslLifecycle.finalizeDsl() - [addBuildTypeUsingDslFinalize](addBuildTypeUsingDslFinalize)
* GeneratesApk.applicationId - [onVariants](onVariants)
* Gradle.beforeProject() - [allProjectsApkAction](allProjectsApkAction)
* HasUnitTestBuilder.enableUnitTest - [selectVariants](selectVariants)
* InAndOutDirectoryOperationRequest.toTransform() - [transformDirectory](transformDirectory)
* InAndOutDirectoryOperationRequest.toTransformMany() - [workerEnabledTransformation](workerEnabledTransformation)
* InAndOutFileOperationRequest.toTransform() - [transformManifest](transformManifest)
* Instrumentation.transformClassesWith() - [asmTransformClasses](asmTransformClasses)
* LifeCycleTasks.registerPreBuild() - [registerPreBuild](registerPreBuild)
* MapProperty.put() - [addCustomBuildConfigFields](addCustomBuildConfigFields), [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* MultipleArtifact.MULTIDEX_KEEP_PROGUARD - [getMultipleArtifact](getMultipleArtifact)
* MultipleArtifact.NATIVE_DEBUG_METADATA - [listenToMultipleArtifact](listenToMultipleArtifact), [appendToMultipleArtifact](appendToMultipleArtifact), [transformMultiple](transformMultiple), [addMultipleArtifact](addMultipleArtifact)
* MultipleArtifactTypeOutOperationRequest.toListenTo() - [listenToMultipleArtifact](listenToMultipleArtifact)
* OutOperationRequest.toAppendTo() - [appendToMultipleArtifact](appendToMultipleArtifact)
* OutOperationRequest.toCreate() - [createSingleArtifact](createSingleArtifact)
* OutOperationRequest.toListenTo() - [listenToArtifacts](listenToArtifacts)
* Plugin<Settings> - [allProjectsApkAction](allProjectsApkAction)
* ResolutionStrategy.dependencySubstitution() - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* ScopedArtifact.CLASSES - [appendToScopedArtifacts](appendToScopedArtifacts), [getScopedArtifacts](getScopedArtifacts), [transformAllClasses](transformAllClasses), [asmTransformClasses](asmTransformClasses)
* ScopedArtifacts.Scope.ALL - [appendToScopedArtifacts](appendToScopedArtifacts), [getScopedArtifacts](getScopedArtifacts)
* ScopedArtifacts.Scope.PROJECT - [appendToScopedArtifacts](appendToScopedArtifacts), [getScopedArtifacts](getScopedArtifacts), [transformAllClasses](transformAllClasses), [asmTransformClasses](asmTransformClasses)
* ScopedArtifacts.use() - [appendToScopedArtifacts](appendToScopedArtifacts), [getScopedArtifacts](getScopedArtifacts), [transformAllClasses](transformAllClasses), [asmTransformClasses](asmTransformClasses)
* ScopedArtifactsOperation.toAppend() - [appendToScopedArtifacts](appendToScopedArtifacts)
* ScopedArtifactsOperation.toGet() - [appendToScopedArtifacts](appendToScopedArtifacts), [getScopedArtifacts](getScopedArtifacts), [asmTransformClasses](asmTransformClasses)
* ScopedArtifactsOperation.toTransform() - [transformAllClasses](transformAllClasses)
* SingleArtifact.APK - [workerEnabledTransformation](workerEnabledTransformation), [allProjectsApkAction](allProjectsApkAction), [listenToArtifacts](listenToArtifacts)
* SingleArtifact.ASSETS - [addGeneratedSourceFolder](addGeneratedSourceFolder), [legacyTaskBridging](legacyTaskBridging), [transformDirectory](transformDirectory)
* SingleArtifact.BUNDLE - [getSingleArtifact](getSingleArtifact), [appendToMultipleArtifact](appendToMultipleArtifact), [addMultipleArtifact](addMultipleArtifact)
* SingleArtifact.MERGED_MANIFEST - [createSingleArtifact](createSingleArtifact), [variantOutput](variantOutput), [transformManifest](transformManifest), [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* SourceDirectories.addGeneratedSourceDirectory() - [addCustomSourceType](addCustomSourceType), [addGeneratedSourceFolder](addGeneratedSourceFolder), [legacyTaskBridging](legacyTaskBridging)
* SourceDirectories.addStaticSourceDirectory() - [addCustomSourceType](addCustomSourceType)
* TaskBasedOperation.wiredWith() - [createSingleArtifact](createSingleArtifact), [transformMultiple](transformMultiple), [listenToArtifacts](listenToArtifacts)
* TaskBasedOperation.wiredWithDirectories() - [workerEnabledTransformation](workerEnabledTransformation), [transformDirectory](transformDirectory)
* TaskBasedOperation.wiredWithFiles() - [transformManifest](transformManifest)
* TaskBasedOperation.wiredWithMultiple() - [listenToMultipleArtifact](listenToMultipleArtifact)
* TaskOutputs.upToDateWhen() - [transformManifest](transformManifest)
* TaskProvider.flatMap() - [createSingleArtifact](createSingleArtifact)
* TaskProvider.map() - [addCustomBuildConfigFields](addCustomBuildConfigFields)
* Variant.buildConfigFields - [addCustomBuildConfigFields](addCustomBuildConfigFields)
* Variant.components - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* Variant.manifestPlaceholders - [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* Variant.nestedComponents - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* VariantBuilder.minSdk - [selectVariants](selectVariants)
* VariantExtensionConfig - [extendingAgp](extendingAgp)
* VariantOutputConfiguration.OutputType.SINGLE - [variantOutput](variantOutput)
* VariantOutputConfiguration.outputType - [variantOutput](variantOutput)
* VariantSelector.all() - [selectVariants](selectVariants), [variantOutput](variantOutput)
* VariantSelector.withBuildType() - [variantDependencySubstitutionTest](variantDependencySubstitutionTest), [selectVariants](selectVariants), [allProjectsApkAction](allProjectsApkAction)
* VariantSelector.withFlavor() - [selectVariants](selectVariants), [variantOutput](variantOutput)
* VariantSelector.withName() - [selectVariants](selectVariants)
* task.getOutputs() - [transformManifest](transformManifest)
## Call chains
* DslExtension.Builder().extendProjectWith().extendBuildTypeWith().extendProductFlavorWith().build() - [extendingAgp](extendingAgp)
* androidComponents.beforeVariants {} - [selectVariants](selectVariants)
* androidComponents.finalizeDsl {} - [addBuildTypeUsingDslFinalize](addBuildTypeUsingDslFinalize)
* androidComponents.onVariants {} - [appendToScopedArtifacts](appendToScopedArtifacts), [listenToMultipleArtifact](listenToMultipleArtifact), [extendingAgp](extendingAgp), [getSingleArtifact](getSingleArtifact), [addCustomSourceType](addCustomSourceType), [getMultipleArtifact](getMultipleArtifact), [getScopedArtifacts](getScopedArtifacts), [transformAllClasses](transformAllClasses), [variantDependencySubstitutionTest](variantDependencySubstitutionTest), [createSingleArtifact](createSingleArtifact), [appendToMultipleArtifact](appendToMultipleArtifact), [onVariants](onVariants), [addCustomBuildConfigFields](addCustomBuildConfigFields), [addGeneratedSourceFolder](addGeneratedSourceFolder), [transformMultiple](transformMultiple), [registerPreBuild](registerPreBuild), [variantOutput](variantOutput), [workerEnabledTransformation](workerEnabledTransformation), [addMultipleArtifact](addMultipleArtifact), [allProjectsApkAction](allProjectsApkAction), [legacyTaskBridging](legacyTaskBridging), [transformManifest](transformManifest), [transformDirectory](transformDirectory), [perVariantManifestPlaceholder](perVariantManifestPlaceholder), [asmTransformClasses](asmTransformClasses), [listenToArtifacts](listenToArtifacts)
* androidComponents.registerExtension() - [extendingAgp](extendingAgp)
* androidComponents.selector().all() - [selectVariants](selectVariants), [variantOutput](variantOutput)
* androidComponents.selector().withBuildType() - [variantDependencySubstitutionTest](variantDependencySubstitutionTest), [selectVariants](selectVariants), [allProjectsApkAction](allProjectsApkAction)
* androidComponents.selector().withFlavor() - [selectVariants](selectVariants), [variantOutput](variantOutput)
* androidComponents.selector().withName() - [selectVariants](selectVariants)
* configuration.resolutionStrategy.dependencySubstitution {} - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* settings.gradle.beforeProject {} - [allProjectsApkAction](allProjectsApkAction)
* substitute().using() - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* task.outputs.upToDateWhen {} - [transformManifest](transformManifest)
* transformationRequest.submit() - [workerEnabledTransformation](workerEnabledTransformation)
* variant.applicationId - [onVariants](onVariants)
* variant.artifacts.add() - [transformMultiple](transformMultiple), [addMultipleArtifact](addMultipleArtifact)
* variant.artifacts.forScope().use().toAppend() - [appendToScopedArtifacts](appendToScopedArtifacts)
* variant.artifacts.forScope().use().toGet() - [getScopedArtifacts](getScopedArtifacts), [asmTransformClasses](asmTransformClasses)
* variant.artifacts.forScope().use().toTransform() - [transformAllClasses](transformAllClasses)
* variant.artifacts.get() - [getSingleArtifact](getSingleArtifact), [appendToMultipleArtifact](appendToMultipleArtifact), [addGeneratedSourceFolder](addGeneratedSourceFolder), [transformMultiple](transformMultiple), [variantOutput](variantOutput), [addMultipleArtifact](addMultipleArtifact), [allProjectsApkAction](allProjectsApkAction), [legacyTaskBridging](legacyTaskBridging), [transformManifest](transformManifest), [transformDirectory](transformDirectory), [perVariantManifestPlaceholder](perVariantManifestPlaceholder), [asmTransformClasses](asmTransformClasses)
* variant.artifacts.getAll() - [getMultipleArtifact](getMultipleArtifact)
* variant.artifacts.use().wiredWith().toAppendTo() - [appendToMultipleArtifact](appendToMultipleArtifact)
* variant.artifacts.use().wiredWith().toCreate() - [createSingleArtifact](createSingleArtifact)
* variant.artifacts.use().wiredWith().toListenTo() - [listenToMultipleArtifact](listenToMultipleArtifact), [listenToArtifacts](listenToArtifacts)
* variant.artifacts.use().wiredWith().toTransform() - [transformMultiple](transformMultiple)
* variant.artifacts.use().wiredWithDirectories().toTransform() - [transformDirectory](transformDirectory)
* variant.artifacts.use().wiredWithDirectories().toTransformMany() - [workerEnabledTransformation](workerEnabledTransformation)
* variant.artifacts.use().wiredWithFiles().toTransform() - [transformManifest](transformManifest)
* variant.buildConfigFields.put() - [addCustomBuildConfigFields](addCustomBuildConfigFields)
* variant.instrumentation.transformClassesWith() - [asmTransformClasses](asmTransformClasses)
* variant.manifestPlaceholders.put() - [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* variant.registerPreBuild() - [registerPreBuild](registerPreBuild)
* variant.sources.*.addGeneratedSourceDirectory() - [addCustomSourceType](addCustomSourceType), [addGeneratedSourceFolder](addGeneratedSourceFolder), [legacyTaskBridging](legacyTaskBridging)
* variant.sources.*.addStaticSourceDirectory() - [addCustomSourceType](addCustomSourceType)
* variant.sources.*.all - [addCustomSourceType](addCustomSourceType), [addGeneratedSourceFolder](addGeneratedSourceFolder)
## Others
* All projects - [allProjectsApkAction](allProjectsApkAction)
* Extending AGP DSL - [extendingAgp](extendingAgp)
* Legacy API bridging - [legacyTaskBridging](legacyTaskBridging)
* Placeholders - [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* Renaming APKs - [listenToArtifacts](listenToArtifacts)
* SourceDirectories.Flat - [addCustomSourceType](addCustomSourceType)
* SourceDirectories.Layered - [addGeneratedSourceFolder](addGeneratedSourceFolder)
* SourceDirectories.add - [addCustomSourceType](addCustomSourceType)
* registerSourceType - [addCustomSourceType](addCustomSourceType)
# License
```
Copyright 2022 The Android Open Source Project

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
