<template>
    <md-tabs>
      <md-tab id="tab-home" md-label="소개">
        <div id=desktop>
            <h1>병천순대거리 소개</h1>
            <div class="md-layout">
                <div class="md-layout-item">
                    <div class="intro">
                        <i class="material-icons">event_note</i>
                        <p>
                            여행,명소 > 먹자거리
                        </p>
                    </div>
                </div>
                <div class="md-layout-item">                                    
                    <div class="time">
                        <i class="material-icons">access_time</i>
                        <p>매일 09:00 - 20:00 (매장마다 상이함</p>
                    </div>
                    <div class="park">
                        <i class="material-icons">local_parking</i>
                        <p>주차가능</p>
                    </div>
                    <div>
                        <i class="material-icons">pin_drop</i>
                        <p>충남 천안시 동남구 병천면 아우내장터길</p>
                    </div>
                </div>
            </div>                
        </div>   
        <div id="tablet">
            <h1>병천순대거리 소개</h1>                        
            <div class="time">
                <i class="material-icons">access_time</i>
                <p>매일 09:00 - 20:00 (매장마다 상이함</p>
            </div>
            <div class="park">
                <i class="material-icons">local_parking</i>
                <p>주차가능</p>
            </div>
            <div>
                <i class="material-icons">pin_drop</i>
                <p>충남 천안시 동남구 병천면 아우내장터길</p>
            </div>
            <hr>            
            <div class="intro">
                <i class="material-icons">event_note</i>
                <p>
                    여행,명소 > 먹자거리
                </p>
            </div>

        </div>
        <div id="mobile">
            <h1>병천순대거리 소개</h1>                        
            <div class="time">
                <i class="material-icons">access_time</i>
                <p>매일 09:00 - 20:00 (매장마다 상이함</p>
            </div>
            <div class="park">
                <i class="material-icons">local_parking</i>
                <p>주차가능</p>
            </div>
            <div>
                <i class="material-icons">pin_drop</i>
                <p>충남 천안시 동남구 병천면 아우내장터길</p>
            </div>
            <hr>            
            <div class="intro">
                <i class="material-icons">event_note</i>
                <p>
                    여행,명소 > 먹자거리
                </p>
            </div>
        </div>
      </md-tab>
      <md-tab id="tab-posts" md-label="전경">
          
      </md-tab>
      <md-tab id="tab-favorites" md-label="방문후기">     
        <div id="desktop">
            <div class="md-layout">
                <div class="md-layout-item">
                    <h1>방명록</h1>
                    
                    <md-card md-with-hover>
                    <md-ripple>
                        <md-card-header>
                        <div class="md-title">순대는 역시!</div>
                        <div class="md-subhead">-10분 전</div>
                        </md-card-header>

                        <md-card-content>
                        병천순대 입니다!!
                        </md-card-content>

                        <md-card-actions>        
                            <md-badge class="md-primary" md-content="34">                
                            <md-button class="md-icon-button ">
                                <md-icon>thumb_up</md-icon>
                            </md-button>
                            </md-badge>
                        </md-card-actions>
                    </md-ripple>
                    </md-card>
                </div>
                <div class="md-layout-item">
                    <md-button class="md-fab md-mini md-plain">
                        <md-icon>edit</md-icon>
                    </md-button>
                    <h1>방명록 쓰기</h1>
                    <md-field>
                    <label>제목</label>
                    <md-input ></md-input>
                    </md-field>
                    <md-field>
                        <label>내용</label>
                        <md-textarea></md-textarea>
                    </md-field>
                </div>
            </div>          
        </div> 
        <div id="tablet">
            <md-button class="md-fab md-mini md-plain">
                <md-icon>edit</md-icon>
            </md-button>
            <h1>방명록 쓰기</h1>
            <md-field>
            <label>제목</label>
            <md-input ></md-input>
            </md-field>
            <md-field>
                <label>내용</label>
                <md-textarea></md-textarea>
            </md-field>
            <hr>
            <h1>방명록</h1>
            
            <md-card md-with-hover>
            <md-ripple>
                <md-card-header>
                <div class="md-title">순대는 역시!</div>
                <div class="md-subhead">-10분 전</div>
                </md-card-header>

                <md-card-content>
                병천순대 입니다!!
                </md-card-content>

                <md-card-actions>        
                    <md-badge class="md-primary" md-content="34">                
                    <md-button class="md-icon-button">
                        <md-icon>thumb_up</md-icon>
                    </md-button>
                    </md-badge>
                </md-card-actions>
            </md-ripple>
            </md-card>
        </div>
        <div id="mobile">
            <md-button class="md-fab md-mini md-plain">
                <md-icon>edit</md-icon>
            </md-button>
            <h1>방명록 쓰기</h1>
            <md-field>
            <label>제목</label>
            <md-input ></md-input>
            </md-field>
            <md-field>
                <label>내용</label>
                <md-textarea></md-textarea>
            </md-field>
            <hr>
            <h1>방명록</h1>
            
            <md-card md-with-hover>
            <md-ripple>
                <md-card-header>
                <div class="md-title">순대는 역시!</div>
                <div class="md-subhead">-10분 전</div>
                </md-card-header>

                <md-card-content>
                병천순대 입니다!!
                </md-card-content>

                <md-card-actions>        
                    <md-badge class="md-primary" md-content="34">                
                    <md-button class="md-icon-button ">
                        <md-icon>thumb_up</md-icon>
                    </md-button>
                    </md-badge>
                </md-card-actions>
            </md-ripple>
            </md-card>
        </div>        
      </md-tab>
    </md-tabs>
</template>

<script>
    export default {
        data(){
              return {
                
              }
            },
        methods: {
            clicked: function () {
                
            }
        }
    }
</script>

<style scoped>
.md-button{
    float: right;
}
    
@media (max-width:799px){
  #desktop{
    display : none;
  }
  #tablet{
    display: none;
  }
  .md-badge{
    display: none;
  }
}
@media only screen and (min-width : 800px) and (max-width : 1023px){  
  #desktop{
    display : none;
  }
  #mobile{
    display : none;
  }  
}
@media only screen and (min-width : 1024px){

    #tablet{
        display: none;
    }
    #mobile{
        display : none;
    }  
    div p{
        display: inline-block;
    }
    .intro p{
        display: inline-block;
    }
    
}
</style>