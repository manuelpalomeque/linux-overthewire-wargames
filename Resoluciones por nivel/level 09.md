Bandit Level 8 → Level 9
Level Goal
The password for the next level is stored in the file data.txt and is the only line of text that occurs only once


     bandit8@bandit:~$ sort data.txt | uniq -u
     EN632PlfYiZbn3PhVK3XOGSlNInNE00t

Otra forma de resolucion, donde con sort ordeno y con la opcion -c cuento cuantas veces se repite la linea:

     bandit8@bandit:~$ sort data.txt | uniq -c 
     10 0OvPFQCx2OI01VN7AwqUcOd4cqR9Ecg9
     10 0TTLuJ0jGXQM5Knk21Ghi4iisHYJOfzI
     10 0V6GeVMoo5JJLhXGq0kEYSEXz1F4RD31
     10 1aj22eYarp5vixqBvRUbsOhBtkdI2yoQ
     10 1wfF9tInmCoPs0YXZiCKbPZJSPn1sEaC
     10 3emkK8imP2xGVGmsyk3pBV3iGN95QWUJ
     10 4GLsgBdz0b1JA8cR5vH9CiX1jCAT3TF1
     10 4nl1vgXcs3wdgdbQjbh6JF4kR2vNUVOK
     10 5jR7RYLuNfGBG86ek0hNFPyVH0jT5alz
     10 67t9oP2hokb2EwnpyVZ9JfX4iPuqFhwN
     10 68qUzJZLuOIw5a6iPi2CVsxlP6l0wgaS
     10 6hXvdZamDJFnfKX8O8UZPVjZpjeqeq6M
     10 7HNLPWyymsBFNjZJVPRro4zPh2p1imsN
     10 7oV07TQQtETcBvqFHtW81o0IQ4H3pc08
     10 7XoqQeNcJ2d6aJDFe0YmKsnuT0IgMUMj
     10 8fPyikNHUu0T0AIm1rq937MITCu70T5b
     10 9e4P3HPx7hhhcuWCMPWwEyDiScykCEVE
     10 9M6SWWGVn01QZkgauxJX8ebx2LN5sOau
     10 9VMVP6eBmQFpfhvnxTey6ZcBbqmqaCAQ
     10 AyLowHutWTI3WLR37pvKFBdxrk0GDuux
     10 B3E7u3CYUKsHrS3FL4OxwnQ8mV41JsmC
     10 B4ZsFwBy6o26IaTRDilVExRxmS6yaiON
     10 bDwxYKyKRyCCg1bVbTUqMOmA5mqBPgXd
     10 bEua052cWOy20ToRoJSMvoadKgbPcbjN
     10 bIGx2gTFaRwyjxyqnsraNKXd8t93eK2D
     10 boosqStx1lFfEEaMoGP6BS78Bw7Fh2xR
     10 DD2JRDeH9vptlOX9jQozH8Moj1xAKl1C
     10 DfjpGIxPR7Q0Wbkxyf4OkV1olJl0njs7
     10 dgvpG7eRY1Dr5HW11ejvuhZvGCAmosTQ
     10 DHMhiE3MDZYEncOWimJaGxkVfAejqL1c
     10 dhoAlBlnhEz2xYyJdfI5ysm0JpyqDkQV
     10 distOgdG7obAspnU4rE1HsWJ2upkf6BK
     10 DItvEOrpT0pRGL1bFdRhoQkwX8SdlMYV
      1 EN632PlfYiZbn3PhVK3XOGSlNInNE00t !!!!!!!! <--
     10 Eor03gLDc3awKULF84XCnD8xgRg6X9S3
     10 F5wqfqjZqVuufXkocZswBcRuVJfMZD0t
     10 fOhFsyegU2D3zLrex0WI9Osw2DlNYIlj
     10 fTS4yCSbaYvGtedvArozwBvT4QJZaY3V
     10 G0Fl2aOBxC5HkgtLFQ3wLOG8kdeFbimU
     10 g3hmwWBu72TrvlJGcH20Z1BUZUjyNEAP
     10 GI718PrXWhEUMrVWHEXeSGq1TrKix5wC
     10 GKeOanTFCdBKLTHVT6aZUxCiBM3Ilz1h
     10 GnVO6bUiehvLjSQafuu0FtLEqDbd9XJk
     10 h44iM4fCazdJGlR3i4QGaSR6FtyGmd4Q
     10 hHkYOknMBcOeDpJtovxn2xyRh8x6WWZN
     10 hisCIm8EcxJQhaaCxGZ5B02d2Pp8YFF2
     10 HqxUEnCqSABq86q6oEXA0cTCRkdXaRGB
     10 i6t6LYg1JArHP57SS8532uSDt6HRA9Ln
     10 I7kIMlx7OwcR0iVcrQcZLkFVKirg6GbH
     10 IqlahKt2QkZPXqMwkgPT4vSnVz5D3krL
     10 iXDaAA9PpACZoerj2tHsLzhE5EgHcUFy
     10 iY3mDCFqYlh5wygRtn1YeU6y0CSNXmKY
     10 jBN1cLA8VHLIWyD7rsg1WULYyDvnMoyA
     10 jmi8Vq4LiDZZcT2Z3WXKiyFrLqKLnobn
     10 K8qwREpxl0kMXAMMwkpo8pVb6u9XwTaM
     10 KASs9h0z0x6kvfX203jFL6n6EZFgKFmK
     10 KNgTMQN5x6a50H6UEQxdEj8nxQkMpapI
     10 LWBFux4a4Tn9nsorjauNGgkYzysEPIKy
     10 memqUIqPxQlPQbgn8sUVH1l4FMYIqONK
     10 mfPt8y5IAlX5FxNm6jQRG7J7F6N0hhq5
     10 MZ6EfG1Kr8ohSuz0itIWofR5k2koEvN6
     10 mzCnXrbqm8QdgjRP1A12isJwyCZ0uTJn
     10 n7daFkUndOrqkC6H8sSWKM7H9X3Ry8nU
     10 nbmIZ2t0tN9WWBbIB9GIhaegyUYcNcaT
     10 nccGlPXq84wMh1MmRwslbtftYJp6M2jw
     10 nH4PmCjbfB2ZCsPcI2ITBiJrhwnalnCw
     10 oOgeByUpG6aVC63M1lIhoHxO3mBo6NUv
     10 oUHk3VaGVlNeB52K6cV03vEPAjMDshRR
     10 Owei9FwGx3FOhhyCOHQbX88R9mo4wvXI
     10 pGUkQwJc3zP4w51Y2G3IfpG5y8Gie3qE
     10 q6yEv3shQ4PN7Ri4hSjxsOHh0gWvvIws
     10 QdyGZKn2feSwyHKHfMARlvEKJiFXpXmx
     10 QrMLTTEu3KGuydS2w9FLTTLzuRldf6f6
     10 RJizoPEBRhVuM5dF8NbRoUAcFgCYxAby
     10 RpOwfRgvra5ZOobMMG0FzLaJLNOUq8IS
     10 rShwnp8z3jpvmYislmcAofYjiy5W8AJN
     10 RydEL1CgSXIaskEkVDSxidIPtGgf79aP
     10 ryM64LqAra2XBhstdzbLWfUS26Xa9o6C
     10 s2ZGuAmX6cY1gJ9ER1qkXDCWTFntPJvJ
     10 S8pD2LpjAMYoiXv8jnKS83awCtQ580mG
     10 tnhOGCM27V5AoOMflWhsZM1EFc8DZe3x
     10 to4dGEh75zmEPDNYE7Q4CpxwwTXE3bt5
     10 TuYdzYVx3Z5ue4jRaOqX3O1qf8Y1M97I
     10 tWXPDAqZ2EEdi0RtFw6fGOzrMLyv45JZ
     10 UPmZTd6oJGLWmYM1dRXgWEKEX4GEs10M
     10 uqX3gQttld1yVlerTi7tWfOJ0YHnBVHl
     10 Uwp7FChAk5XZlN7hP6EHzp2kYNMiGJxA
     10 vCV4xQA9BY6D78vlljAq3SEFY7mGeLJd
     10 vud4cV2mrjB0ejsvILxKm9T4SuMqnmFj
     10 w3HlpqT7lMjCE3GqwOr16jvDW0BICYKr
     10 wN85lAbx5wkDs0IfVpbI1dSUSgY16Qml
     10 XCAk2n2alytIxQABvtUUjqAL4I4Cchdm
     10 xuois4H0D8w4Y5o01Dqh335oIMYOpo0O
     10 YKJ6eP4J17SQu0N6PNcstsHp88AxzLCm
     10 Yo6Vkk3oHp6Lbcwhip2BGNfTmJvrPVLX
     10 Yr8T84ODrPJztEfP3dASzTMxCREEFvR0
     10 Yyv6mm6Vw4sTRZiM0Z4AaK88KcLElw4N
     10 Z8ncb64yvxMpYu6kyuRadwjouYpkMLPN
     10 ZeUYvhRpgIJkdO9FQpoVXvkukvDGiFKD
     10 zJmXl1uLmwGC7r6mhGj1MJ0WEepnHSoT
     10 Zull6EmfASvJeHFJD9cgOWF9BsR51e4s

