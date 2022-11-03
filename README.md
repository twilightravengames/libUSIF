
# libUSIF
Universal Skeletal Interchange Format - a library of skeleton rigging algorithms and utilities for use with USD and the CMV-SDK

RDS documents specifically target USIF rigged models or dynamically converted models with physics simulatino data as well to update their rigging for contiguous metaverse purposes.

# NOTES

libUSIF contains the following submodules:

RDSApply - Applies RDS data to a piece of geometry with a USIF skeleton
DualQuadToLinearTools - A set of algorithms and tools to convert DualQuaternion skin-binding data to linear skin-binding data (MOrph Target Systems)
DualQuadToUSIF - A set of algorithsm and tools to convert DualQuaternion skin-binding data to USIF data (Morph target systems)
LinearBlendToUSIF - A set of algorithms and tools to convert Linear Blend skin-binding data to USIF data (Morph target systems)
IKToUSIF - A set of algorithms and tools to convert Inverse Kinematics rigged models to USFIF data
FKTOUSIF - a set of algorithsm and tools to convert Forward Kinematics rigged models to USIF data
USIFPPluginInterface - An API/SDK to write plugins to convert other skeletal animation algorithms to USIF
