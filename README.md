# ThickLine

VRML PROTO (based on `Extrusion`) that generates a 3D line with adjustable thickness.

	EXTERNPROTO ThickLine [
		exposedField  MFVec3f  spine
		exposedField  SFFloat  thickness
		exposedField  SFFloat  thicknessTesselation
		field         SFFloat  creaseAngle
		field         SFBool   beginCap
		field         SFBool   endCap
	] "proto.ThickLine.wrl#ThickLine"


-------------------------------------------------------------------------------

## Property `spine`

Like `Extrusion.spine`, it defines the 3D path of the line.

Definition:
 - Field Type: `exposedField`
 - Data Type: `MFVec3f`
 - Default Value: `[]`


-------------------------------------------------------------------------------

## Property `thickness`

Width of the line (bigger number = thicker).

Definition:
 - Field Type: `exposedField`
 - Data Type: `SFFloat`
 - Default Value: `0.1`


-------------------------------------------------------------------------------

## Property `thicknessTesselation`

Number of vertices on the extrusion section (bigger number = higher resolution tube).

Definition:
 - Field Type: `exposedField`
 - Data Type: `SFFloat`
 - Default Value: `4`


-------------------------------------------------------------------------------

## Property `creaseAngle`

Like `Extrusion.creaseAngle`.

Definition:
 - Field Type: `field`
 - Data Type: `SFFloat`
 - Default Value: `0`


-------------------------------------------------------------------------------

## Property `beginCap`

Like `Extrusion.beginCap`.

Definition:
 - Field Type: `field`
 - Data Type: `SFBool`
 - Default Value: `TRUE`


-------------------------------------------------------------------------------

## Property `endCap`

Like `Extrusion.endCap`.

Definition:
 - Field Type: `field`
 - Data Type: `SFBool`
 - Default Value: `TRUE`


-------------------------------------------------------------------------------

