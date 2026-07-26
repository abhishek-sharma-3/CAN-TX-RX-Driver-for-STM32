#ifndef CAN_DRIVER_H_
#define CAN_DRIVER_H_
#include "STM32F4xx.h"


#define CAN_ID_STD  0x00

#define CAN_ID_EXT  0x01



typedef struct
{
	uint32_t std_id;
	uint32_t ext_id;
	uint32_t ide;
	uint32_t rtr;
	uint32_t dlc;
	uint8_t transmit_global_time;
}can_tx_header_typedef;
typedef struct
{
	uint32_t std_id;
	uint32_t ext_id;
	uint32_t ide;
	uint32_t rtr;
	uint32_t dlc;
	uint32_t timedstamp;
	uint32_t filter_match_index;
}can_rx_header_typedef;
#endif
