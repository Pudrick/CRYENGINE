#START-FILE-LIST
# File List auto generated by waf2cmake.py, do not modify manually.

start_sources()
# -- plugin.waf_files --
sources_platform(ALL)
add_sources("CryDefaultEntities_uber_0.cpp"
	SOURCE_GROUP "Legacy\\\\Audio"
		"Legacy/Audio/AudioAreaEntity.cpp"
		"Legacy/Audio/AudioAreaEntity.h"
		"Legacy/Audio/AudioAreaRandom.cpp"
		"Legacy/Audio/AudioAreaRandom.h"
		"Legacy/Audio/AudioAreaAmbienceEntity.cpp"
		"Legacy/Audio/AudioAreaAmbienceEntity.h"
		"Legacy/Audio/AudioTriggerSpotEntity.cpp"
		"Legacy/Audio/AudioTriggerSpotEntity.h"
		"Legacy/Audio/AudioEntitiesUtils.h"
		"Legacy/Audio/AudioEntitiesUtils.cpp"
	SOURCE_GROUP "Legacy\\\\Cameras"
		"Legacy/Cameras/CameraSource.cpp"
		"Legacy/Cameras/CameraSource.h"
	SOURCE_GROUP "Legacy\\\\Debug"
		"Legacy/Debug/Comment.cpp"
		"Legacy/Debug/Comment.h"
	SOURCE_GROUP "Legacy\\\\Geometry"
		"Legacy/Geometry/GeomEntity.cpp"
		"Legacy/Geometry/GeomEntity.h"
	SOURCE_GROUP "Legacy\\\\Helpers"
		"Legacy/Helpers/DesignerEntityComponent.cpp"
		"Legacy/Helpers/DesignerEntityComponent.h"
		"Legacy/Helpers/EntityFlowNode.cpp"
		"Legacy/Helpers/EntityFlowNode.h"
	SOURCE_GROUP "Legacy\\\\Lights"
		"Legacy/Lights/EnvironmentProbe.cpp"
		"Legacy/Lights/EnvironmentProbe.h"
		"Legacy/Lights/LightEntity.cpp"
		"Legacy/Lights/LightEntity.h"
	SOURCE_GROUP "Legacy\\\\Particles"
		"Legacy/Particles/ParticleEntity.cpp"
		"Legacy/Particles/ParticleEntity.h"
	SOURCE_GROUP "Legacy\\\\Physics"
		"Legacy/Physics/RopeEntity.cpp"
		"Legacy/Physics/LocalGrid.cpp"
		"Legacy/Physics/LocalGrid.h"
	SOURCE_GROUP "Legacy\\\\Triggers"
		"Legacy/Triggers/TriggerEntity.cpp"
		"Legacy/Triggers/TriggerEntity.h"
	SOURCE_GROUP "Lights"
		"DefaultComponents/Lights/EnvironmentProbeComponent.cpp"
		"DefaultComponents/Lights/EnvironmentProbeComponent.h"
		"DefaultComponents/Lights/PointLightComponent.cpp"
		"DefaultComponents/Lights/PointLightComponent.h"
		"DefaultComponents/Lights/ILightComponent.h"
		"DefaultComponents/Lights/ProjectorLightComponent.cpp"
		"DefaultComponents/Lights/ProjectorLightComponent.h"
	SOURCE_GROUP "Geometry"
		"DefaultComponents/Geometry/BaseMeshComponent.cpp"
		"DefaultComponents/Geometry/BaseMeshComponent.h"
		"DefaultComponents/Geometry/StaticMeshComponent.cpp"
		"DefaultComponents/Geometry/StaticMeshComponent.h"
		"DefaultComponents/Geometry/AnimatedMeshComponent.cpp"
		"DefaultComponents/Geometry/AnimatedMeshComponent.h"
		"DefaultComponents/Geometry/AdvancedAnimationComponent.cpp"
		"DefaultComponents/Geometry/AdvancedAnimationComponent.h"
		"DefaultComponents/Geometry/AlembicComponent.cpp"
		"DefaultComponents/Geometry/AlembicComponent.h"
	SOURCE_GROUP "Effects"
		"DefaultComponents/Effects/ParticleComponent.cpp"
		"DefaultComponents/Effects/ParticleComponent.h"
		"DefaultComponents/Effects/FogComponent.cpp"
		"DefaultComponents/Effects/FogComponent.h"
		"DefaultComponents/Effects/DecalComponent.cpp"
		"DefaultComponents/Effects/DecalComponent.h"
		"DefaultComponents/Effects/WaterRippleComponent.cpp"
		"DefaultComponents/Effects/WaterRippleComponent.h"
		"DefaultComponents/Effects/RainComponent.cpp"
		"DefaultComponents/Effects/RainComponent.h"
	SOURCE_GROUP "Debug"
		"DefaultComponents/Debug/DebugDrawComponent.cpp"
		"DefaultComponents/Debug/DebugDrawComponent.h"
	SOURCE_GROUP "Constraints"
		"DefaultComponents/Constraints/PointConstraint.cpp"
		"DefaultComponents/Constraints/PointConstraint.h"
		"DefaultComponents/Constraints/LineConstraint.cpp"
		"DefaultComponents/Constraints/LineConstraint.h"
		"DefaultComponents/Constraints/PlaneConstraint.cpp"
		"DefaultComponents/Constraints/PlaneConstraint.h"
		"DefaultComponents/Constraints/BreakableJoint.cpp"
		"DefaultComponents/Constraints/BreakableJoint.h"
	SOURCE_GROUP "Cameras"
		"DefaultComponents/Cameras/CameraComponent.cpp"
		"DefaultComponents/Cameras/CameraComponent.h"
		"DefaultComponents/Cameras/CameraManager.h"
		"DefaultComponents/Cameras/ICameraManager.h"
	SOURCE_GROUP "Cameras\\\\VirtualReality"
		"DefaultComponents/Cameras/VirtualReality/RoomscaleCamera.cpp"
		"DefaultComponents/Cameras/VirtualReality/RoomscaleCamera.h"
	SOURCE_GROUP "Physics"
		"DefaultComponents/Physics/CharacterControllerComponent.cpp"
		"DefaultComponents/Physics/CharacterControllerComponent.h"
		"DefaultComponents/Physics/RigidBodyComponent.cpp"
		"DefaultComponents/Physics/RigidBodyComponent.h"
		"DefaultComponents/Physics/RagdollComponent.cpp"
		"DefaultComponents/Physics/RagdollComponent.h"
		"DefaultComponents/Physics/ParticleComponent.cpp"
		"DefaultComponents/Physics/ParticleComponent.h"
		"DefaultComponents/Physics/PhysicsPrimitiveComponent.cpp"
		"DefaultComponents/Physics/PhysicsPrimitiveComponent.h"
		"DefaultComponents/Physics/BoxPrimitiveComponent.cpp"
		"DefaultComponents/Physics/BoxPrimitiveComponent.h"
		"DefaultComponents/Physics/SpherePrimitiveComponent.cpp"
		"DefaultComponents/Physics/SpherePrimitiveComponent.h"
		"DefaultComponents/Physics/CapsulePrimitiveComponent.cpp"
		"DefaultComponents/Physics/CapsulePrimitiveComponent.h"
		"DefaultComponents/Physics/CylinderPrimitiveComponent.cpp"
		"DefaultComponents/Physics/CylinderPrimitiveComponent.h"
		"DefaultComponents/Physics/ThrusterComponent.cpp"
		"DefaultComponents/Physics/ThrusterComponent.h"
		"DefaultComponents/Physics/AreaComponent.cpp"
		"DefaultComponents/Physics/AreaComponent.h"
		"DefaultComponents/Physics/SampleRigidbodyActorComponent.cpp"
		"DefaultComponents/Physics/SampleRigidbodyActorComponent.h"
		"DefaultComponents/Physics/LocalGridComponent.cpp"
		"DefaultComponents/Physics/LocalGridComponent.h"
		"DefaultComponents/Physics/ClothComponent.cpp"
		"DefaultComponents/Physics/ClothComponent.h"
		"DefaultComponents/Physics/WaterVolumeComponent.cpp"
		"DefaultComponents/Physics/WaterVolumeComponent.h"
	SOURCE_GROUP "Physics\\\\Vehicles"
		"DefaultComponents/Physics/Vehicles/VehicleComponent.cpp"
		"DefaultComponents/Physics/Vehicles/VehicleComponent.h"
		"DefaultComponents/Physics/Vehicles/WheelComponent.cpp"
		"DefaultComponents/Physics/Vehicles/WheelComponent.h"
	SOURCE_GROUP "Physics\\\\VirtualReality"
		"DefaultComponents/Physics/VirtualReality/VirtualRealityInteractionComponent.cpp"
		"DefaultComponents/Physics/VirtualReality/VirtualRealityInteractionComponent.h"
	SOURCE_GROUP "Input"
		"DefaultComponents/Input/InputComponent.cpp"
		"DefaultComponents/Input/InputComponent.h"
	SOURCE_GROUP "Audio"
		"DefaultComponents/Audio/AreaComponent.cpp"
		"DefaultComponents/Audio/AreaComponent.h"
		"DefaultComponents/Audio/DefaultTriggerComponent.cpp"
		"DefaultComponents/Audio/DefaultTriggerComponent.h"
		"DefaultComponents/Audio/EnvironmentComponent.cpp"
		"DefaultComponents/Audio/EnvironmentComponent.h"
		"DefaultComponents/Audio/ListenerComponent.cpp"
		"DefaultComponents/Audio/ListenerComponent.h"
		"DefaultComponents/Audio/MultiListenerComponent.cpp"
		"DefaultComponents/Audio/MultiListenerComponent.h"
		"DefaultComponents/Audio/OcclusionComponent.cpp"
		"DefaultComponents/Audio/OcclusionComponent.h"
		"DefaultComponents/Audio/ParameterComponent.cpp"
		"DefaultComponents/Audio/ParameterComponent.h"
		"DefaultComponents/Audio/PreloadComponent.cpp"
		"DefaultComponents/Audio/PreloadComponent.h"
		"DefaultComponents/Audio/SettingComponent.cpp"
		"DefaultComponents/Audio/SettingComponent.h"
		"DefaultComponents/Audio/SwitchStateComponent.cpp"
		"DefaultComponents/Audio/SwitchStateComponent.h"
		"DefaultComponents/Audio/TriggerComponent.cpp"
		"DefaultComponents/Audio/TriggerComponent.h"
		"DefaultComponents/Audio/VelocityComponent.cpp"
		"DefaultComponents/Audio/VelocityComponent.h"
	SOURCE_GROUP "Utilities"
		"DefaultComponents/Utilities/ChildEntityComponent.cpp"
		"DefaultComponents/Utilities/ChildEntityComponent.h"
	SOURCE_GROUP "ComponentHelpers"
		"DefaultComponents/ComponentHelpers/PhysicsParameters.h"
	SOURCE_GROUP "Root"
		"PluginDll.cpp"
		"PluginDll.h"
		"IDefaultComponentsPlugin.h"
		"resource.h"
		"StdAfx.cpp"
		"StdAfx.h"
)

add_sources("NoUberFile"
	SOURCE_GROUP "Root"
		"StdAfx.cpp"
)

end_sources()
#END-FILE-LIST

CryEngineModule(CryDefaultEntities PCH "StdAfx.cpp" SOLUTION_FOLDER "CryPlugins")

if(WINDOWS)
	target_compile_options(${THIS_PROJECT} PRIVATE /Zc:inline-)
endif()

target_include_directories(${THIS_PROJECT}
PRIVATE
	"${CRYENGINE_DIR}/Code/CryEngine/CryCommon"
	# Remove when we've switched to entity components
	"${CRYENGINE_DIR}/Code/CryEngine/CryAction"
PUBLIC
	.
)

if (ORBIS OR CMAKE_CXX_COMPILER_ID STREQUAL "Clang")
	target_compile_options(${THIS_PROJECT} PRIVATE
		-Wno-reorder
		-Wno-unknown-pragmas
		-Wno-parentheses
		-Wno-switch
		-Wno-format
		-Wno-char-subscripts
		-Wno-empty-body
		-Wno-multichar
		-Wno-unused-value
		-Wno-null-conversion
		-Wno-unused-value
		-Wno-unused-private-field
		-Wno-unused-function
		-Wno-c++11-narrowing
		-Wno-dynamic-class-memaccess
		-Wno-sometimes-uninitialized
	)
elseif(CMAKE_CXX_COMPILER_ID STREQUAL "GNU")
	target_compile_options(${THIS_PROJECT} PRIVATE
		-Wno-unused-function
		-Wno-unused-value
		-Wno-sign-compare
		-Wno-unused-but-set-variable
		-Wno-misleading-indentation
		-Wno-unknown-pragmas
		-Wno-maybe-uninitialized
		-Wno-array-bounds
		-Wno-unused-result
		-Wno-strict-aliasing
		-Wno-multichar
		-Wno-char-subscripts
		-Wno-conversion-null
		-Wno-reorder
		-Wno-parentheses
		-Wno-format
		-Wno-switch
	)
endif()
