# Approach

Use built-in 2D rendering and physics, a static circular fulcrum, a dynamic plank attached by HingeJoint2D, and two dynamic players. The supplied CharacterController2DP2.cs remains unchanged. John explicitly permits one separate input script to read both keyboard layouts, call Move, choose animations and handle restart. No editor helper scripts are included.

A scripted plank angle would ignore player weight, so use native Rigidbody2D and joint physics. Keep graphics and colliders separately sized to avoid stretching artwork.

Target the confirmed lab editor, Unity 6000.2.2f1. The home PC currently has only 6000.5.10f1; checks with that editor must be labelled separately from a 6000.2.2f1 lab check.
