# UE5_RigSkeletalMesh
Retargeting animations in Unreal Engine allows you to use an animation created for one skeletal mesh with another.


# Steps to Retarget Animations:

# 1. Set Up IK Rig for Both Skeletons

Create IK Rig assets for both the source (original) and target skeletons.

	•	Source Skeleton IK Rig:
	•	Right-click in the Content Browser.
	•	Navigate to Animation > IK Rig.
	•	Select the source skeleton (the skeleton with the animations you want to retarget).
	•	Target Skeleton IK Rig:
	•	Repeat the above steps, but this time select the target skeleton (the skeleton you want to apply the animations to).

# 2. Create an IK Retargeter

	•	Right-click in the Content Browser and select Animation > IK Retargeter.
	•	Choose the source IK Rig when prompted.
	•	Open the IK Retargeter and select the target IK Rig from the drop-down menu at the top-right.

# 3. Map Bones

	•	Ensure that bones are correctly mapped between the source and target skeletons.
	•	Adjust bone mappings manually if needed to improve animation results.

# 4. Retarget the Animation

	•	In the IK Retargeter window, select the animations to retarget from the left-hand panel.
	•	Click Retarget Animation Assets and choose a folder to save the new animation assets.

# 5. Test Retargeted Animations

	•	Apply the new animation assets to the target skeletal mesh.
	•	If adjustments are necessary, go back to the IK Retargeter to fine-tune the retarget pose or bone mapping.

Additional Notes:

	•	Ensure that the source and target skeletons have a similar hierarchy for best results.
	•	Root motion can be adjusted in the animation asset after retargeting if required.

This file outlines the basic steps for retargeting animations in Unreal Engine and can be customized further if needed.
