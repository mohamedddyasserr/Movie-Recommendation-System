# Movie Recommendation System 

## Overview  
This project implements a **movie recommendation system** using collaborative filtering techniques. We explore three approaches:  
- **User-Based Collaborative Filtering (User-CF)**  
- **Item-Based Collaborative Filtering (Item-CF)**  
- **Matrix Factorization with Truncated SVD (SVD)**  

The workflow is structured across three Jupyter notebooks:  
1. **Data Setup** → load and inspect the dataset.  
2. **Preprocessing** → prepare user-item matrices and clean the data.  
3. **Modeling (Collaborative Filtering)** → implement recommendation algorithms and evaluate their performance.  

---

## Dataset  
We use the **MovieLens 100K dataset**, which contains:  
- Users, movies, and ratings.  
- Ratings are explicit (1–5 scale).  
- Metadata such as movie titles is also available for mapping.  

---

## Project Workflow  
1. **Data Setup**  
   - Loaded the MovieLens dataset.  
   - Inspected structure, checked for missing values.  

2. **Preprocessing**  
   - Built the **user-item rating matrix**.  
   - Applied **cosine similarity** for users and items.  
   - Prepared input for SVD.  

3. **Modeling**  
   - **User-Based CF** → recommends movies based on similar users.  
   - **Item-Based CF** → recommends movies based on similar items.  
   - **SVD (Truncated SVD)** → learns latent factors for users and items.  

4. **Evaluation**  
   - Used **Precision@5** and **Recall@5** to measure model effectiveness.  

---

## Evaluation Results  

| Model      | Precision@5 | Recall@5 |
|------------|-------------|----------|
| User-CF    | **0.316**   | **0.738** |
| Item-CF    | **0.356**   | **0.785** |
| SVD        | **0.361**   | **0.804** |

**Observation**: SVD performs best, followed by Item-CF, then User-CF.  

---

## Conclusion  
- All models provide meaningful recommendations.  
- **User-CF** works but is the weakest.  
- **Item-CF** improves precision and recall.  
- **SVD** achieves the best performance, showing the benefit of latent factor models.  
- The system demonstrates how collaborative filtering can be effectively applied to movie recommendation tasks.  

---

## Author  
<div>
<table align="center">
  <tr>    </td>
    </td>
        <td align="center">
      <a href="https://github.com/mohamedddyasserr" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/126451832?v=4" width="150px;" alt="Mohamed Yasser"/>
        <br />
        <sub><b>Mohamed Yasser</b></sub>
      </a>
    </td>    
  </tr>
</table>
</div>
  
 
