while wait() do
local args = {
    [1] = Vector3.new(1005.6182250976562, 133.55479431152344, 607.1004028320312)
}

game:GetService("ReplicatedStorage"):WaitForChild("Event"):WaitForChild("Snowball"):FireServer(unpack(args))
end
