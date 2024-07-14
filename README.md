# MuiltiPlayerUnityAssignment
Its a Muiltiplyer 2D app who uses Photon for networking
im aware that i was supposed to make a app in which a player collides with other we get connected by audio chat and video chat with that player but the agora_gaming_rtc namespace was not there in the agora video sdk , i checked and downloaded every version available for agora video sdk but the namespace was not available in any of those
i tried reimporting the agora sdk but it didn't work

these 2 errors i was facing 
Assets\Scripts\AgoraManager.cs(2,7): error CS0246: The type or namespace name 'agora_gaming_rtc' could not be found (are you missing a using directive or an assembly reference?)
Assets\Scripts\AgoraManager.cs(8,13): error CS0246: The type or namespace name 'IRtcEngine' could not be found (are you missing a using directive or an assembly reference?)
