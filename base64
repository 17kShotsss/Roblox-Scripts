local output
if option == "encode" then
    output = base64encode(text)
elseif option == "decode" then
    output = base64decode(text)
else
    error("invalid option: "..option)
end

if result == "print" then
    print(output)
elseif result == "clipboard" then
    setclipboard(output)
else
    error("invalid result: "..result)
end
