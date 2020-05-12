import androidx.annotation.NonNull;
import androidx.annotation.Nullable;
import androidx.room.ColumnInfo;
import androidx.room.Entity;
import androidx.room.PrimaryKey;

@Entity(tableName = "curiosities")

public class Curiosity {

    @PrimaryKey(autoGenerate = true)
    @NonNull
    @ColumnInfo(name = "curiosityId")
    private int mId;

    @Nullable
    @ColumnInfo(name = "curiosityName")
    private String mName;

    public Empathy(String creationDate, String description, String howDidYouNow, int importance) {
        mCreationDate = creationDate;
        mDescription = description;
        mHowDidYouNow = howDidYouNow;
        mImportance = importance;

    }

    public int getId() {
        return mId;
    }

    public void setId(@NonNull int id) {
        mId = id;
    }

    public String getCreationDate() {
        return mCreationDate;
    }

    public void setCreationDate(@Nullable String creationDate) {
        mCreationDate = creationDate;
    }

    public String getDescription() {
        return mDescription;
    }

    public void setDescription(@Nullable String description) {
        mDescription = description;
    }

    public String getHowDidYouNow() {
        return mHowDidYouNow;
    }

    public void setHowDidYouNow(@Nullable String houDidYouNow) {
        mHowDidYouNow = howDidYouNow;
    }

    private String mCreationDate;
 
    private String mDescription;

    private String mHowDidYouNow;

    public int getImportance() {
        return mImportance;
    }

    public void setImportance(@NonNull int importance) {
        mImportance = importance;
    }

    private int mImportance;

    



}
    






