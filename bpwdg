import string
import random


def random_beeline_routers_pwds():
    while True:
        chars = string.ascii_uppercase + string.ascii_lowercase + string.digits
        size = 8

        generated_pwd = ''.join(random.choice(chars) for x in range(size))
        print(generated_pwd)

        f = open("beeline_pwd_generator.txt", 'a')
        f.write(generated_pwd + "\n")
        f.close()


random_beeline_routers_pwds()
