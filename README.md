# Hello, folks! <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px"> :brazil: :netherlands:

func getFlag(country:String) -> String { 
        let base : UInt32 = 127397
        var s = ""
        for v in country.unicodeScalars {
            s.unicodeScalars.append(UnicodeScalar(base + v.value)!)
        }
        return String(s)
    }

About me:
- I’m a veterinarian 🐷 🐮 🐔 epidemiologist 📈 📉 📊 
- 🔭 I’m currently working on Wageningen Bioveterinary Institute
- 🌱 I’m currently learning epidemiology (always)
- 📫 How to reach me: eduardo.costa@wur.nl

[![Eduardo's GitHub stats](https://github-readme-stats.vercel.app/api?username=eduardodefreitascosta)](https://github.com/eduardodefreitascosta/github-readme-stats) [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=eduardodefreitascosta&layout=compact)](https://github.com/eduardodefreitascosta/github-readme-stats)


