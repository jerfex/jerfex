 public class ProgramadorAnalista {

  public static void main(String[] args) {
    String nome = "Jerfeson";
    String formacao = "Análise de Sistemas";
    boolean experiencia = true;
    boolean conhecimentosETL = true;
    String[] habilidades = {
      "UX",
      "Design",
      "Java",
      "Shell script",
      "HTML5",
      "CSS3",
      "Android",
      "Flutter",
      "DevOps",
      "ETL"
    };

    System.out.println("Olá, sou " + nome + ", um programador e analista de sistemas formado em " + formacao + ". Tenho experiência em desenvolvimento de software e DevOps, além de conhecimentos em ETL (Extração, Transformação e Carga) para a integração de dados.");
    System.out.println("Sempre busco me atualizar sobre as novas tendências e tecnologias do mercado para oferecer as melhores soluções aos meus clientes e projetos.");
    System.out.println("Minhas habilidades incluem:");
    for (String habilidade: habilidades) {
      System.out.println("#" + habilidade);
    }
    System.out.println("Acredito que a tecnologia é uma ferramenta poderosa para ajudar as empresas e organizações a alcançarem seus objetivos.");
  }
}
