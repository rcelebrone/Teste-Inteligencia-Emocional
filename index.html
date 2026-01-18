import React, { useState } from 'react';
import { ChevronRight, RefreshCcw, CheckCircle, Award, Brain, Heart, Users, MessageCircle } from 'lucide-react';

const questions = [
  { id: 1, text: "Você sabe identificar as emoções que sente?", pillar: "Autoconsciência" },
  { id: 2, text: "Você sabe se acalmar quando se sente inquieto ou chateado?", pillar: "Autogestão" },
  { id: 3, text: "Você define metas a longo prazo?", pillar: "Autogestão" },
  { id: 4, text: "Você procura entendimento mútuo nas questões?", pillar: "Consciência Social" },
  { id: 5, text: "Você é um bom ouvinte?", pillar: "Gestão de Relacionamentos" },
  { id: 6, text: "Você persiste na busca por seus objetivos, apesar dos obstáculos?", pillar: "Autogestão" },
  { id: 7, text: "Você consegue admitir facilmente que cometeu um erro?", pillar: "Autogestão" },
  { id: 8, text: "Você sabe suas qualidades e defeitos?", pillar: "Autoconsciência" },
  { id: 9, text: "Você promove conversas difíceis para resolver problemas?", pillar: "Gestão de Relacionamentos" },
  { id: 10, text: "Você tenta enxergar as situações pela perspectiva dos outros?", pillar: "Consciência Social" },
  { id: 11, text: "Você tem ânimo para atingir seus objetivos?", pillar: "Autogestão" },
  { id: 12, text: "Você consegue pensar claramente quando está sob pressão?", pillar: "Autogestão" },
  { id: 13, text: "Você utiliza as críticas para crescer?", pillar: "Autoconsciência" },
  { id: 14, text: "Você acha fácil ler as emoções dos outros?", pillar: "Consciência Social" },
  { id: 15, text: "Você lida com pessoas e situações difíceis com delicadeza?", pillar: "Gestão de Relacionamentos" },
  { id: 16, text: "Você se orienta pelos seus valores e objetivos?", pillar: "Autogestão" },
  { id: 17, text: "Você supera facilmente o sentimento de frustração?", pillar: "Autogestão" },
  { id: 18, text: "Você reconhece como seu comportamento afeta os outros?", pillar: "Autoconsciência" },
  { id: 19, text: "Você consegue ouvir sem julgar?", pillar: "Consciência Social" },
  { id: 20, text: "Você presta atenção aos seus relacionamentos?", pillar: "Gestão de Relacionamentos" }
];

const options = [
  { text: "Sempre", value: 5 },
  { text: "Frequentemente", value: 4 },
  { text: "De vez em quando", value: 3 },
  { text: "Raramente", value: 2 },
  { text: "Nunca", value: 1 }
];

const resultsData = [
  {
    min: 20,
    max: 39,
    title: "Necessita Atenção",
    color: "text-red-600",
    bg: "bg-red-50",
    border: "border-red-200",
    description: "Você precisa trabalhar para desenvolver sua inteligência emocional. Apesar de sua sinceridade ser admirável, é provável que você se sinta sobrecarregado por suas emoções e lute para gerenciá-las. Reagir a isso explodindo ou, pelo contrário, não expressando suas emoções, é igualmente prejudicial. Suas respostas às pressões comuns da vida podem estar baseadas no medo e na insegurança. Trabalhe sua autoconsciência, pois ela é o primeiro fundamento da inteligência emocional."
  },
  {
    min: 40,
    max: 59,
    title: "Nível Baixo",
    color: "text-orange-600",
    bg: "bg-orange-50",
    border: "border-orange-200",
    description: "Seu nível de inteligência emocional ainda é um pouco baixo. Você tem mais dificuldade nas situações que exigem habilidades de interação social. É provável que se sinta frequentemente frustrado com colegas ou entes queridos. Comece a trabalhar o autoconhecimento. Entenda quais habilidades são mais difíceis para você (empatia, receber críticas, etc.) e pratique-as."
  },
  {
    min: 60,
    max: 79,
    title: "Bom Nível",
    color: "text-blue-600",
    bg: "bg-blue-50",
    border: "border-blue-200",
    description: "Bom nível de inteligência emocional. É bem provável que você seja sensível às emoções dos que estão ao seu redor. Você também tem consciência sobre o efeito do seu comportamento nos outros. Não tenha medo de se comunicar honestamente e mostrar seus sentimentos, desde que com habilidade."
  },
  {
    min: 80,
    max: 100,
    title: "Nível Excelente (ou Alerta)",
    color: "text-green-600",
    bg: "bg-green-50",
    border: "border-green-200",
    description: "Seus resultados indicam um nível extremamente alto ou, paradoxalmente, muito baixo devido à falta de autoconsciência. Se for fruto de autoconhecimento elevado: ótimo! Continue aprendendo. Se for falta de autocrítica: lembre-se que é preciso ser autoconsciente para se avaliar com precisão. A autoconsciência reflete diretamente nas outras habilidades."
  }
];

const pillars = {
  "Autoconsciência": { icon: Brain, description: "Capacidade de reconhecer as próprias emoções." },
  "Autogestão": { icon: Award, description: "Capacidade de lidar com suas próprias emoções e colocá-las a serviço de um objetivo." },
  "Consciência Social": { icon: Heart, description: "Capacidade de enxergar as situações pela perspectiva dos outros." },
  "Gestão de Relacionamentos": { icon: Users, description: "Conjunto de habilidades envolvidas na interação social." }
};

export default function App() {
  const [screen, setScreen] = useState('start'); // start, quiz, result
  const [answers, setAnswers] = useState({});
  const [currentQuestionIndex, setCurrentQuestionIndex] = useState(0);

  const handleStart = () => {
    setScreen('quiz');
    setCurrentQuestionIndex(0);
    setAnswers({});
  };

  const handleAnswer = (value) => {
    const currentQ = questions[currentQuestionIndex];
    setAnswers(prev => ({ ...prev, [currentQ.id]: value }));
    
    // Smooth scroll to top for mobile feeling
    window.scrollTo(0, 0);

    if (currentQuestionIndex < questions.length - 1) {
      setTimeout(() => setCurrentQuestionIndex(prev => prev + 1), 250);
    } else {
      setTimeout(() => setScreen('result'), 250);
    }
  };

  const calculateScore = () => {
    return Object.values(answers).reduce((a, b) => a + b, 0);
  };

  const calculatePillarScores = () => {
    const pillarScores = {
      "Autoconsciência": { score: 0, total: 0 },
      "Autogestão": { score: 0, total: 0 },
      "Consciência Social": { score: 0, total: 0 },
      "Gestão de Relacionamentos": { score: 0, total: 0 }
    };

    questions.forEach(q => {
      if (answers[q.id]) {
        pillarScores[q.pillar].score += answers[q.id];
        pillarScores[q.pillar].total += 5; // max score per question is 5
      }
    });

    return pillarScores;
  };

  const getResultFeedback = (score) => {
    return resultsData.find(r => score >= r.min && score <= r.max) || resultsData[0];
  };

  const restartQuiz = () => {
    setScreen('start');
    setAnswers({});
    setCurrentQuestionIndex(0);
  };

  // --- SCREENS ---

  const StartScreen = () => (
    <div className="flex flex-col items-center justify-center min-h-screen bg-gradient-to-br from-indigo-50 to-purple-100 p-6 text-center">
      <div className="bg-white p-8 rounded-2xl shadow-xl max-w-lg w-full transition-all hover:shadow-2xl">
        <div className="mb-6 flex justify-center">
          <div className="p-4 bg-indigo-100 rounded-full">
            <Brain className="w-12 h-12 text-indigo-600" />
          </div>
        </div>
        <h1 className="text-3xl font-bold text-gray-800 mb-4">Teste de Inteligência Emocional</h1>
        <p className="text-gray-600 mb-6 leading-relaxed">
          Descubra o seu nível de inteligência emocional. Pessoas com altos níveis conseguem criar relacionamentos mais significativos e lidar melhor com adversidades.
        </p>
        <div className="bg-blue-50 p-4 rounded-lg mb-8 text-sm text-blue-800 text-left">
          <strong>Instruções:</strong> Responda com sinceridade, baseando-se em como você <em>realmente é</em>, e não em como gostaria de ser.
        </div>
        <button 
          onClick={handleStart}
          className="w-full bg-indigo-600 hover:bg-indigo-700 text-white font-bold py-4 px-8 rounded-xl flex items-center justify-center transition-all transform active:scale-95 shadow-lg"
        >
          Iniciar Teste <ChevronRight className="ml-2 w-5 h-5" />
        </button>
      </div>
      <p className="mt-8 text-gray-400 text-xs">Baseado no material "Nível de Inteligência Emocional"</p>
    </div>
  );

  const QuizScreen = () => {
    const question = questions[currentQuestionIndex];
    const progress = ((currentQuestionIndex + 1) / questions.length) * 100;

    return (
      <div className="min-h-screen bg-gray-50 flex flex-col items-center py-10 px-4">
        <div className="w-full max-w-xl">
          {/* Header & Progress */}
          <div className="mb-8">
            <div className="flex justify-between items-end mb-2">
              <span className="text-sm font-semibold text-gray-500 uppercase tracking-wider">Questão {currentQuestionIndex + 1} de {questions.length}</span>
              <span className="text-xs font-bold text-indigo-600 bg-indigo-100 px-2 py-1 rounded">{question.pillar}</span>
            </div>
            <div className="h-2 bg-gray-200 rounded-full overflow-hidden">
              <div 
                className="h-full bg-indigo-600 transition-all duration-500 ease-out"
                style={{ width: `${progress}%` }}
              />
            </div>
          </div>

          {/* Question Card */}
          <div className="bg-white rounded-2xl shadow-lg p-6 md:p-10 mb-6">
            <h2 className="text-2xl md:text-3xl font-bold text-gray-800 mb-8 leading-tight">
              {question.text}
            </h2>

            <div className="space-y-3">
              {options.map((opt) => (
                <button
                  key={opt.value}
                  onClick={() => handleAnswer(opt.value)}
                  className={`w-full text-left p-4 rounded-xl border-2 transition-all duration-200 flex items-center justify-between group
                    ${answers[question.id] === opt.value 
                      ? 'border-indigo-600 bg-indigo-50 text-indigo-700 font-semibold' 
                      : 'border-gray-100 hover:border-indigo-200 hover:bg-gray-50 text-gray-600'
                    }`}
                >
                  <span>{opt.text}</span>
                  {answers[question.id] === opt.value && <CheckCircle className="w-5 h-5 text-indigo-600" />}
                </button>
              ))}
            </div>
          </div>
        </div>
      </div>
    );
  };

  const ResultScreen = () => {
    const totalScore = calculateScore();
    const result = getResultFeedback(totalScore);
    const pillarScores = calculatePillarScores();

    return (
      <div className="min-h-screen bg-gray-50 py-10 px-4">
        <div className="max-w-3xl mx-auto">
          
          {/* Main Score Card */}
          <div className={`bg-white rounded-2xl shadow-xl overflow-hidden mb-8 border-t-8 ${result.color.replace('text-', 'border-')}`}>
            <div className={`p-8 md:p-12 text-center ${result.bg}`}>
              <h2 className="text-gray-500 font-semibold uppercase tracking-wide mb-2">Sua Pontuação Final</h2>
              <div className={`text-6xl md:text-7xl font-black mb-4 ${result.color}`}>
                {totalScore}
                <span className="text-2xl text-gray-400 font-normal">/100</span>
              </div>
              <h3 className={`text-2xl md:text-3xl font-bold mb-4 ${result.color}`}>{result.title}</h3>
            </div>
            <div className="p-8 md:p-12">
              <p className="text-gray-700 leading-relaxed text-lg mb-6">
                {result.description}
              </p>
              <div className="bg-gray-50 p-4 rounded-lg border border-gray-100">
                <p className="text-sm text-gray-500 italic text-center">
                  "A autoconsciência é a capacidade fundamental da inteligência emocional, porque ela reflete diretamente nas outras."
                </p>
              </div>
            </div>
          </div>

          {/* Pillars Breakdown */}
          <div className="grid grid-cols-1 md:grid-cols-2 gap-6 mb-10">
            {Object.entries(pillarScores).map(([name, data]) => {
              const PillarIcon = pillars[name].icon;
              const percentage = Math.round((data.score / data.total) * 100);
              
              return (
                <div key={name} className="bg-white p-6 rounded-xl shadow-sm border border-gray-100 hover:shadow-md transition-shadow">
                  <div className="flex items-center mb-4">
                    <div className="p-2 bg-indigo-50 rounded-lg mr-3">
                      <PillarIcon className="w-6 h-6 text-indigo-600" />
                    </div>
                    <h4 className="font-bold text-gray-800">{name}</h4>
                  </div>
                  
                  <div className="mb-2 flex justify-between text-sm">
                    <span className="text-gray-500">Pontuação</span>
                    <span className="font-bold text-indigo-600">{data.score}/{data.total}</span>
                  </div>
                  
                  <div className="h-2 bg-gray-100 rounded-full overflow-hidden mb-3">
                    <div 
                      className={`h-full rounded-full ${percentage >= 70 ? 'bg-green-500' : percentage >= 40 ? 'bg-yellow-400' : 'bg-red-400'}`} 
                      style={{ width: `${percentage}%` }}
                    />
                  </div>
                  
                  <p className="text-xs text-gray-500 leading-snug">
                    {pillars[name].description}
                  </p>
                </div>
              );
            })}
          </div>

          <div className="text-center">
            <button 
              onClick={restartQuiz}
              className="bg-white border-2 border-gray-200 text-gray-600 hover:border-indigo-600 hover:text-indigo-600 font-bold py-3 px-8 rounded-xl inline-flex items-center transition-all"
            >
              <RefreshCcw className="mr-2 w-4 h-4" /> Refazer Teste
            </button>
          </div>

        </div>
      </div>
    );
  };

  return (
    <div className="font-sans antialiased text-gray-900">
      {screen === 'start' && <StartScreen />}
      {screen === 'quiz' && <QuizScreen />}
      {screen === 'result' && <ResultScreen />}
    </div>
  );
}

