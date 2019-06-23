+++
title = "About"
+++

{{< highlight python >}}

class About:

    def name(self):
        return "Pouriya Jahanbakhsh"

    def birthday(self):
        return "1995/2/25"

    def job(self):
        return "Software Programmer"

    def programming_languages(self):
        # min: 1 & max: 5
        return {
            "Erlang/OTP": 5,
            "Python":     4,
            "AWK":        4,
            "C":          3,
            "Elixir":     3,
            "Sh":         3,
            "Ruby":       2,
            "Perl":       1,
            "Go":         1,
            "Rust":       1
        }

    def operating_systems(self):
        # min: 1 & max: 5
        return {"FreeBSD": 4, "GNU/Linux": 3}

    def databases(self):
        # min: 1 & max: 5
        return {"Cassandra": 3, "Influxdb": 3, "MySQL": 2, "MariaDB": 2}

           

{{< / highlight >}}
