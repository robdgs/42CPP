NAME = megaphone
SRC = megaphone.cpp
CC = c++
CFLAGS = -Wall -Wextra -Werror -std=c++98
RM = rm -f

all: ${NAME}

${NAME} : ${SRC}
	${CC} ${CFLAGS} ${SRC} -o ${NAME}

clean:
	${RM}
fclean: clean
	${RM} ${NAME}
re:
	fclean all

.PHONY: all clean fclean re

