h = game.Players.LocalPlayer.Character.Humanoid

tracks = h:GetPlayingAnimationTracks()

for _,x in pairs(tracks)

do x:Stop()

end
