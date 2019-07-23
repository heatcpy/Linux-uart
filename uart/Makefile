CC = gcc

OBJS =  stm32_uart




all:$(OBJS)

%:%.c
	$(CC) -o $@ $^ -lpthread

clean:
	$(RM) $(OBJS)


