--bincoExit
addEvent("bincoExit", true)
addEventHandler("bincoExit", getRootElement(),
    function(currentBinco)
        
    end
)

--bincoBuySkin
addEvent("bincoBuySkin", true)
addEventHandler("bincoBuySkin", getRootElement(),
    function(skin)
        if skin then
            setElementModel(client, skin)
            setElementData(client, "char.Skin", skin)
        end
    end
)

--bincoEnter
addEvent("bincoEnter", true)
addEventHandler("bincoEnter", getRootElement(),
    function(currentBinco)

    end
)

--bincoGuiFinal trigger
--gotGroupSkinsForBinco trigger
