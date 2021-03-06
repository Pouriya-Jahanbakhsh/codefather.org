+++
title = "About"
date  = 2019-01-01T00:00:00
+++

{{< highlight python >}}

class About:

    def name(self):
        return "Pouriya Jahanbakhsh"

    def job(self):
        return "Software Programmer"

    def programming_languages(self):
        # The ability to get things done
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
        return {"FreeBSD": 4, "GNU/Linux": 3}

    def databases(self):
        return {
            "Cassandra": 3,
            "Influxdb":  3,
            "MySQL":     3,
            "MariaDB":   3
        }

    def message_brokers(self):
        return {
            "Ejabberd":   5,
            "MongooseIM": 3,
            "Kafka":      3
        }

    def techinal_skills(self):
        return {
            "Functional programming":  4,
            "Socket programming":      4,
            "Test Driven Development": 4,
            "Monitoring":              3
        }

    def country(self):
        return "Iran"

    def email(self):
        return "pouriya.jb" + "@" + "gmail.com"

    def phone_number():
        return "+989195458500"

    def github(self):
        return "https://github.com/pouriya-jahanbakhsh"

{{< / highlight >}}


