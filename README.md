# stonejam6-Components
A bunch of components for StoneScript. JSON Parser, string extensión, array extension...


## JSON Parse
var json=import Components/JSON

json.Parse("[array]")	// converts string to data

json.Stringify([array])	// converts data to string

## String extension
var stringExt=import Components/String

stringExt.Pad(str,len,char)

stringExt.PadR(str,len,char)

stringExt.PadL(str,len,char)

stringExt.Repeat(str,len)

## Array extension
var arrayExt=import Components/Array

arrayExt.Slice(arr,from,length)	// returns a portion of arr

arrayExt.Pop(arr)

arrayExt.Shift(arr)

arrayExt.Unshift(arr,value)

## Storage extension
var storageExt=import Components/Storage

storageExt.GetArray("key",[array])  // get saved data from local storage, as array

storageExt.SetArray("key",[array])  // save array in local storage

