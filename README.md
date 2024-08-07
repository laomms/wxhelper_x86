https://github.com/ttttupup/wxhelper  重编译版
适用于3.9.2.23 [download] (https://github.com/tom-snow/wechat-windows-versions/releases/download/v3.9.2.23/WeChatSetup-3.9.2.23.exe)

```c++
// snsDataMgr
#define WX_SNS_DATA_MGR_OFFSET 0xc39680
// chatRoomMgr
#define WX_CHAT_ROOM_MGR_OFFSET 0x78cf20
// contactMgr
#define WX_CONTACT_MGR_OFFSET 0x75a4a0
// syncMgr
#define WX_SYNC_MGR_OFFSET 0xa87fd0
// preDownloadMgr
#define WX_GET_PRE_DOWNLOAD_MGR_OFFSET 0x80f110
// chatMgr
#define WX_CHAT_MGR_OFFSET 0x792700
// videoMgr
#define WX_VIDEO_MGR_OFFSET 0x829820
// patMgr
#define  WX_PAT_MGR_OFFSET  0x931730
// searchContactMgr
#define WX_SEARCH_CONTACT_MGR_OFFSET 0xa6cb00
// appMsgMgr
#define WX_APP_MSG_MGR_OFFSET   0x76ae20
// sendMessageMgr
#define WX_SEND_MESSAGE_MGR_OFFSET 0x768140
// shareRecordMgr
#define WX_SHARE_RECORD_MGR_OFFSET 0x78cb40    
// headImageMgr
#define WX_HEAD_IMAGE_MGR_OFFSET 0x807b00


// setChatMsgValue
#define WX_INIT_CHAT_MSG_OFFSET 0xf59e40

// chatMsg
#define WX_NEW_CHAT_MSG_OFFSET 0x76f010
#define WX_FREE_CHAT_MSG_OFFSET 0x756960
// #define WX_FREE_CHAT_MSG_2_OFFSET 0x6f4ea0
#define WX_FREE_CHAT_MSG_INSTANCE_COUNTER_OFFSET 0x756e30


//sns
#define WX_SNS_GET_FIRST_PAGE_OFFSET 0x14e2140
#define WX_SNS_GET_NEXT_PAGE_OFFSET  0x14e21e0

//chat room
#define WX_GET_CHAT_ROOM_DETAIL_INFO_OFFSET 0xbde090
// chatRoomInfo
#define WX_NEW_CHAT_ROOM_INFO_OFFSET 0xe99c40
#define WX_FREE_CHAT_ROOM_INFO_OFFSET 0xe99f40
#define WX_DEL_CHAT_ROOM_MEMBER_OFFSET 0xbd22a0
#define WX_ADD_MEMBER_TO_CHAT_ROOM_OFFSET 0xbd1dc0
 

// chatRoom
#define WX_INIT_CHAT_ROOM_OFFSET 0xe97890
#define WX_FREE_CHAT_ROOM_OFFSET 0xe97ab0

#define WX_GET_MEMBER_FROM_CHAT_ROOM_OFFSET 0xbdf260
#define WX_MOD_CHAT_ROOM_MEMBER_NICK_NAME_OFFSET 0xbd9680

#define WX_TOP_MSG_OFFSET 0xbe1840
#define WX_REMOVE_TOP_MSG_OFFSET 0xbe1620

#define WX_GET_MEMBER_NICKNAME_OFFSET  0xbdf3f0

#define WX_FREE_CONTACT_OFFSET  0xea7880

// wcpayinfo
#define WX_NEW_WCPAYINFO_OFFSET 0x7b2e60
#define WX_FREE_WCPAYINFO_OFFSET 0x79c250
#define WX_CONFIRM_RECEIPT_OFFSET 0x15e2c20


//contact
#define WX_CONTACT_GET_LIST_OFFSET 0xc089f0
#define WX_CONTACT_DEL_OFFSET 0xb9b3b0

#define WX_SET_VALUE_OFFSET 0x1f80900
#define WX_DO_DEL_CONTACT_OFFSET 0xca6480
#define WX_GET_CONTACT_OFFSET  0xc04e00
#define WX_DO_VERIFY_USER_OFFSET  0xc02100
#define WX_VERIFY_MSG_OFFSET  0xf59d40
#define WX_VERIFY_OK_OFFSET  0xa18bd0
#define WX_NEW_ADD_FRIEND_HELPER_OFFSET 0xa17d50
#define WX_FREE_ADD_FRIEND_HELPER_OFFSET 0xa17e70
#define WX_MOD_REMARK_OFFSET  0xbfd5e0

// pushAttachTask


#define WX_PUSH_ATTACH_TASK_OFFSET 0x82bb40

#define WX_GET_MGR_BY_PREFIX_LOCAL_ID_OFFSET 0xbc0370
#define WX_APP_MSG_INFO_OFFSET 0x7b3d20
#define WX_GET_APP_MSG_XML_OFFSET 0xe628a0
#define WX_FREE_APP_MSG_INFO_OFFSET 0x79d900
#define WX_PUSH_THUMB_TASK_OFFSET 0x82ba40
#define WX_DOWNLOAD_VIDEO_IMG_OFFSET 0xd46c30


// revoke
#define WX_REVOKE_MSG_OFFSET 0xbb5f70


// pat
#define  WX_SEND_PAT_MSG_OFFSET  0x1421940
#define  WX_RET_OFFSET   0x1D58751


//search hook
#define WX_SEARCH_CONTACT_ERROR_CODE_HOOK_OFFSET 0xe17054
#define WX_SEARCH_CONTACT_ERROR_CODE_HOOK_NEXT_OFFSET 0xf57a20
#define WX_SEARCH_CONTACT_DETAIL_HOOK_OFFSET 0xa8ceb0
#define WX_SEARCH_CONTACT_DETAIL_HOOK_NEXT_OFFSET 0xa8d100
#define WX_SEARCH_CONTACT_OFFSET 0xcd1510



//login
#define WX_LOGIN_URL_OFFSET 0x3040DE8
#define WX_LOGOUT_OFFSET 0xe58870
#define WX_ACCOUNT_SERVICE_OFFSET 0x768c80
#define WX_GET_APP_DATA_SAVE_PATH_OFFSET 0xf3a610
#define WX_GET_CURRENT_DATA_PATH_OFFSET 0xc872c0
#define WX_QR_CODE_LOGIN_MGR_OFFSET  0xae9db0
#define WX_GET_QR_CODE_IMAGE_OFFSET   0xcda6f0
 
//forward
#define WX_FORWARD_MSG_OFFSET 0xce6730
// send file
#define WX_SEND_FILE_OFFSET     0xb6d1f0
// send image
#define WX_SEND_IMAGE_OFFSET  0xce6640
// send text
#define WX_SEND_TEXT_OFFSET 0xce6c80


//ocr
#define WX_INIT_OBJ_OFFSET 0x80a800
#define WX_OCR_MANAGER_OFFSET 0x80f270
#define WX_DO_OCR_TASK_OFFSET 0x13da3e0


//storage

#define CONTACT_G_PINSTANCE_OFFSET 0x2ffddc8
#define DB_MICRO_MSG_OFFSET 0x68
#define DB_CHAT_MSG_OFFSET 0x1C0
#define DB_MISC_OFFSET 0x3D8
#define DB_EMOTION_OFFSET 0x558
#define DB_MEDIA_OFFSET 0x9B8
#define DB_BIZCHAT_MSG_OFFSET 0x1120
#define DB_FUNCTION_MSG_OFFSET 0x11B0
#define DB_NAME_OFFSET 0x14

#define STORAGE_START_OFFSET  0x13f8
#define STORAGE_END_OFFSET  0x13fc

#define PUBLIC_MSG_MGR_OFFSET  0x303df74
#define MULTI_DB_MSG_MGR_OFFSET  0x30403b8
#define FAVORITE_STORAGE_MGR_OFFSET  0x303fd40
#define FTS_FAVORITE_MGR_OFFSET  0x2ffe908

#define OP_LOG_STORAGE_VFTABLE 0x2AD3A20
#define CHAT_MSG_STORAGE_VFTABLE 0x2AC10F0
#define CHAT_CR_MSG_STORAGE_VFTABLE 0x2ABEF14
#define SESSION_STORAGE_VFTABLE 0x2AD3578
#define APP_INFO_STORAGE_VFTABLE 0x2ABCC58
#define HEAD_IMG_STORAGE_VFTABLE 0x2ACD9DC
#define HEAD_IMG_URL_STORAGE_VFTABLE 0x2ACDF70

#define BIZ_INFO_STORAGE_VFTABLE 0x2ABD718
#define TICKET_INFO_STORAGE_VFTABLE 0x2AD5400
#define CHAT_ROOM_STORAGE_VFTABLE 0x2AC299C
#define CHAT_ROOM_INFO_STORAGE_VFTABLE 0x2AC245C
#define MEDIA_STORAGE_VFTABLE 0x2ACE998
#define NAME_2_ID_STORAGE_VFTABLE 0x2AD222C
#define EMOTION_PACKAGE_STORAGE_VFTABLE 0x2AC6400

#define EMOTION_STORAGE_VFTABLE 0x2AC7018
#define BUFINFO_STORAGE_VFTABLE 0x2AC3178

#define CUSTOM_EMOTION_STORAGE_VFTABLE 0x2AC4E90
#define DEL_SESSIONINFO_STORAGE_VFTABLE 0x2AC5F98
#define FUNCTION_MSG_STORAGE_VFTABLE 0x2ACD10C

#define FUNCTION_MSG_TASK_STORAGE_VFTABLE 0x2ACC5C8
#define REVOKE_MSG_STORAGE_VFTABLE 0x2AD27BC



// public msg forward

#define NEW_MM_READ_ITEM_OFFSET  0x76e630
#define FREE_MM_READ_ITEM_OFFSET  0x76da30
#define FREE_MM_READ_ITEM_2_OFFSET  0x76e350
#define FORWARD_PUBLIC_MSG_OFFSET  0xb73000


// send app msg
#define NEW_SHARE_APP_MSG_REQ_OFFSET 0xfb9890
// #define FREE_SHARE_APP_MSG_REQ_OFFSET 0xfbc0d0
#define FREE_SHARE_APP_MSG_REQ_OFFSET 0xfbab40
#define NEW_WA_UPDATABLE_MSG_INFO_OFFSET 0x7b3290
#define FREE_WA_UPDATABLE_MSG_INFO_OFFSET 0x79ca10
#define SEND_APP_MSG_OFFSET 0xfe7840

// query head image  then download 
#define QUERY_THEN_DOWNLOAD_OFFSET  0xc63470


/*******************hook*********************************************/  


// hook image
#define WX_HOOK_IMG_OFFSET 0xd723dc
#define WX_HOOK_IMG_NEXT_OFFSET 0xe91d90



// hook log
#define WX_HOOK_LOG_OFFSET 0xf57d67
#define WX_HOOK_LOG_NEXT_OFFSET 0x240ea71

// hook msg

#define WX_RECV_MSG_HOOK_OFFSET 0xd19a0b
#define WX_RECV_MSG_HOOK_NEXT_OFFSET 0x756960
#define WX_SNS_HOOK_OFFSET  0x14f9e15
#define WX_SNS_HOOK_NEXT_OFFSET 0x14fa0a0


// hook voice
#define WX_HOOK_VOICE_OFFSET 0xd4d8d8
#define WX_HOOK_VOICE_NEXT_OFFSET 0x203d130
#define WX_SELF_ID_OFFSET 0x2FFD484  

```
