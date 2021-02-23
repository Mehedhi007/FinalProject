Hello Bhaia Take Salam,

I have watched your videos and  few youtube videos to get idea. I have included the routes below.

Kind Regards.





Route::get('/',[StudentController::class,'index']) ;
Route::get('/edit/{id}',[StudentController::class,'edit']) ;
Route::get('/show/{id}',[StudentController::class,'show']) ;
Route::get('/create',[StudentController::class,'create']) ;
Route::post('/store',[StudentController::class,'store']) ;
Route::post('/update/{id}',[StudentController::class,'update']) ;