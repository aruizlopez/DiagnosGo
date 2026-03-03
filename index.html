import React, { useState, useEffect, useRef } from 'react';
import {
  Camera,
  Settings,
  Monitor,
  Smartphone,
  Power,
  Layers,
  RefreshCw,
  CheckCircle2,
  ClipboardList,
  UserCheck,
  Activity,
  History,
  User,
  Sliders,
  Crosshair,
  Scan,
  Waves,
  Zap,  
  Magnet,
  MapPin,
  Stethoscope,
  Scissors,
  CalendarDays,
  Loader2,
  FileText,
  Clock
} from 'lucide-react';


// --- Componente del Logo ---
const DiagnosGoLogo = ({ mode = "full" }) => {
  const isMini = mode === "mini";
  return (
    <div className={`flex ${isMini ? 'flex-row items-center gap-3' : 'flex-col items-center'} font-mono uppercase italic`}>
      {!isMini && <span className="text-white font-black tracking-[0.5em] text-lg mb-4">DIAGNOS</span>}
      <div className={`relative flex items-center justify-center ${isMini ? 'w-10 h-10' : 'w-48 h-48'}`}>
        {!isMini && <span className="text-white font-black text-5xl absolute -left-12 bottom-12">G</span>}
        <div className="relative w-full h-full flex items-center justify-center overflow-hidden">
          <svg viewBox="0 0 100 100" className="w-full h-full drop-shadow-[0_0_15px_rgba(59,130,246,0.6)]">
            <path d="M50 88 C18 68 5 48 5 28 A15 15 0 0 1 48 28 L50 30 L52 28 A15 15 0 0 1 95 28 C95 48 82 68 50 88 Z" fill="none" stroke="#3b82f6" strokeWidth="4" strokeLinecap="round" />
            <path d="M15 45 L35 45 L40 35 L45 55 L50 45 L55 45 L60 30 L65 60 L70 45 L85 45" fill="none" stroke="#3b82f6" strokeWidth="1" strokeOpacity="0.3" strokeDasharray="2 2" />
            <g fill="white">
              <circle cx="50" cy="35" r="5" />
              <line x1="50" y1="40" x2="50" y2="60" stroke="white" strokeWidth="4" strokeLinecap="round" />
              <path d="M50 45 L35 32" stroke="white" strokeWidth="4" strokeLinecap="round" />
              <path d="M50 45 L65 32" stroke="white" strokeWidth="4" strokeLinecap="round" />
              <path d="M50 60 L40 80" stroke="white" strokeWidth="4" strokeLinecap="round" />
              <path d="M50 60 L60 80" stroke="white" strokeWidth="4" strokeLinecap="round" />
            </g>
            <line x1="10" y1="0" x2="90" y2="0" stroke="#60a5fa" strokeWidth="2" strokeOpacity="0.8">
              <animateTransform attributeName="transform" type="translate" from="0 25" to="0 85" dur="3s" repeatCount="indefinite" />
            </line>
          </svg>
        </div>
        {!isMini && <span className="text-white font-black text-5xl absolute -right-12 bottom-12">O</span>}
      </div>
      {isMini && (
        <div className="flex flex-col leading-none">
          <span className="text-[8px] text-white font-black tracking-widest">DIAGNOS</span>
          <span className="text-blue-500 font-black text-sm tracking-widest">G O</span>
        </div>
      )}
    </div>
  );
};


// --- Formulario de Login ---
const PatientForm = ({ onConfirm }) => {
  const [formData, setFormData] = useState({ id: '', doctor: '', password: '', date: '2026-03-03' });
  const authorizedDoctors = ["marta martin perez", "ana ruiz lopez", "marta martín pérez", "ana ruiz lópez"];
  const normalizeText = (text) => text.toLowerCase().trim();
  const isDoctorValid = authorizedDoctors.includes(normalizeText(formData.doctor));
  const isPasswordValid = formData.password === "0000";
  const canAccess = isDoctorValid && formData.id.length >= 4 && isPasswordValid;


  return (
    <div className="absolute inset-0 bg-slate-950 z-[100] flex flex-col items-center justify-center p-4">
      <div className="w-full max-w-lg flex flex-col items-center gap-12">
        <DiagnosGoLogo mode="full" />
        <div className="w-full max-w-md bg-[#0a0f1a]/80 p-8 rounded-[2rem] border border-white/10 backdrop-blur-md shadow-2xl">
          <div className="space-y-4">
            <input type="text" placeholder="ID PACIENTE" className="w-full bg-black/40 border border-slate-800 rounded-xl p-4 text-xs text-center outline-none focus:border-blue-500 font-mono text-white tracking-widest uppercase" onChange={(e) => setFormData({...formData, id: e.target.value})} />
            <div className="relative">
              <input type="text" placeholder="MÉDICO FACULTATIVO" className="w-full bg-black/40 border border-slate-800 rounded-xl p-4 text-xs text-center outline-none focus:border-blue-500 font-mono text-white tracking-widest uppercase" onChange={(e) => setFormData({...formData, doctor: e.target.value})} />
              {formData.doctor && !isDoctorValid && (
                <p className="absolute -bottom-5 left-0 w-full text-center text-[8px] text-red-500 font-bold animate-pulse">FACULTATIVO NO RECONOCIDO</p>
              )}
            </div>
            <div className="grid grid-cols-2 gap-4 pt-2">
              <input type="date" value={formData.date} className="bg-black/40 border border-slate-800 rounded-xl p-3 text-[10px] text-white font-mono" onChange={(e) => setFormData({...formData, date: e.target.value})} />
              <input type="password" placeholder="PIN" className="bg-black/40 border border-slate-800 rounded-xl p-3 text-xs text-center font-mono text-white tracking-[0.5em]" onChange={(e) => setFormData({...formData, password: e.target.value})} />
            </div>
            <button onClick={() => onConfirm(formData)} disabled={!canAccess} className="w-full bg-blue-600/20 hover:bg-blue-600 border border-blue-500/30 py-4 rounded-xl font-black text-[10px] disabled:opacity-10 uppercase tracking-[0.3em] transition-all flex items-center justify-center gap-2 mt-2">
              <UserCheck size={16} /> Iniciar Sesión
            </button>
          </div>
        </div>
      </div>
    </div>
  );
};


export default function App() {
  const [isSessionActive, setIsSessionActive] = useState(false);
  const [activeTab, setActiveTab] = useState('scan');
  const [showProfile, setShowProfile] = useState(false);
 
  const [testType, setTestType] = useState('RADIOGRAFÍA');
  const [isAnalyzing, setIsAnalyzing] = useState(false);
  const [analysisResult, setAnalysisResult] = useState(null);
  const [scanProgress, setScanProgress] = useState(0);
  const [reliabilityLevel, setReliabilityLevel] = useState(95);
  const [scanHistory, setScanHistory] = useState([]);
 
  const [cameraActive, setCameraActive] = useState(false);
  const [isSimulationMode, setIsSimulationMode] = useState(false);
  const videoRef = useRef(null);


  const [patientData, setPatientData] = useState({
    id: '', doctor: '', date: '', address: '', pathologies: '', operations: '', birthYear: '', photo: ''
  });


  const generateRandomPatientData = (baseData) => {
    const addresses = ["Calle Mayor 45, Madrid", "Av. de la Constitución 12, Sevilla", "Gran Via 789, Barcelona", "Calle Larios 4, Málaga"];
    const pathologyList = ["Hipertensión Arterial", "Diabetes Tipo II", "Asma Crónica", "Arritmia Sinusal", "Ninguna destacable"];
    const surgeryList = ["Apendicectomía (2015)", "Fractura de fémur (2020)", "Colecistectomía (2018)", "Ninguna previa"];
    const years = ["1965", "1978", "1985", "1992", "2001", "1954"];
    const randomSeed = Math.floor(Math.random() * 1000);
    const photoUrl = `https://api.dicebear.com/7.x/avataaars/svg?seed=${randomSeed}`;


    return {
      ...baseData,
      address: addresses[Math.floor(Math.random() * addresses.length)],
      pathologies: pathologyList[Math.floor(Math.random() * pathologyList.length)],
      operations: surgeryList[Math.floor(Math.random() * surgeryList.length)],
      birthYear: years[Math.floor(Math.random() * years.length)],
      photo: photoUrl
    };
  };


  const startCamera = async () => {
    try {
      const stream = await navigator.mediaDevices.getUserMedia({
        video: { facingMode: 'environment', width: 1280, height: 720 }
      });
      if (videoRef.current) {
        videoRef.current.srcObject = stream;
        setCameraActive(true);
        setIsSimulationMode(false);
      }
    } catch (err) {
      setCameraActive(true);
      setIsSimulationMode(true);
    }
  };


  const stopCamera = () => {
    if (videoRef.current && videoRef.current.srcObject) {
      const tracks = videoRef.current.srcObject.getTracks();
      tracks.forEach(track => track.stop());
      videoRef.current.srcObject = null;
    }
    setCameraActive(false);
  };


  const generateAIIcon = async (prompt) => {
    const apiKey = "";
    try {
      const response = await fetch(`https://generativelanguage.googleapis.com/v1beta/models/imagen-4.0-generate-001:predict?key=${apiKey}`, {
        method: "POST",
        headers: { "Content-Type": "application/json" },
        body: JSON.stringify({
          instances: { prompt: prompt },
          parameters: { sampleCount: 1 }
        })
      });
      const result = await response.json();
      return `data:image/png;base64,${result.predictions[0].bytesBase64Encoded}`;
    } catch (error) {
      return `https://placehold.co/600x400/0f172a/3b82f6?text=IA+DIAGNOSIS:+${encodeURIComponent(prompt)}`;
    }
  };


  const handleStartAnalysis = async () => {
    if (!cameraActive) {
      startCamera();
      return;
    }


    setIsAnalyzing(true);
    setScanProgress(0);
    setAnalysisResult(null);


    const bodyParts = ["BRAZO", "PIERNA", "TORAX", "CABEZA", "MANO", "COLUMNA"];
    const partDetected = bodyParts[Math.floor(Math.random() * bodyParts.length)];


    const interval = setInterval(() => {
      setScanProgress(p => (p >= 100 ? 100 : p + 5));
    }, 100);


    const diagnosisMatrix = {
      'RADIOGRAFÍA': {
        'BRAZO': 'FRACTURA CERRADA DE CÚBITO Y RADIO',
        'PIERNA': 'ROTURA DE TIBIA DIAFISARIA',
        'TORAX': 'NEUMOTÓRAX LADO DERECHO',
        'CABEZA': 'FISURA CRANEAL SIN DESPLAZAMIENTO',
        'MANO': 'DISLOCACIÓN CARPIANA',
        'COLUMNA': 'ESCOLIOSIS LUMBAR SEVERA'
      },
      'ECOGRAFÍA': {
        'BRAZO': 'INFLAMACIÓN DE TENDONES EXTENSORES',
        'PIERNA': 'DERRAME SINOVIAL EN RODILLA',
        'TORAX': 'LÍQUIDO EN PLEURA DETECTADO',
        'CABEZA': 'FLUJO SANGUÍNEO CEREBRAL NORMAL',
        'MANO': 'TENOSINOVITIS DE QUERVAIN',
        'COLUMNA': 'HERNIA DISCAL L4-L5'
      },
      'RESONANCIA': {
        'BRAZO': 'ROTURA DE MANGUITO ROTADOR',
        'PIERNA': 'LESIÓN DE LIGAMENTO CRUZADO ANTERIOR',
        'TORAX': 'MASA MEDIASTÍNICA NO IDENTIFICADA',
        'CABEZA': 'INFARTO LACUNAR AGUDO',
        'MANO': 'ARTRITIS REUMATOIDE INCIPIENTE',
        'COLUMNA': 'ESTENOSIS DEL CANAL MEDULAR'
      }
    };


    const diagnosis = diagnosisMatrix[testType][partDetected];
    const prompt = `Realistic medical ${testType.toLowerCase()} of a ${partDetected.toLowerCase()}, showing ${diagnosis.toLowerCase()}, high contrast, clinical details`;
   
    const aiImageUrl = await generateAIIcon(prompt);


    setTimeout(() => {
      clearInterval(interval);
      setIsAnalyzing(false);
      const result = {
        id: Date.now(),
        patientId: patientData.id,
        timestamp: new Date().toLocaleTimeString(),
        diagnosis: diagnosis,
        part: partDetected,
        confidence: `${(reliabilityLevel + (Math.random() * (100 - reliabilityLevel))).toFixed(1)}%`,
        image: aiImageUrl,
        type: testType
      };
      setAnalysisResult(result);
      // Guardar en el historial de la sesión
      setScanHistory(prev => [result, ...prev]);
    }, 2500);
  };


  useEffect(() => {
    if (!isSessionActive) {
      stopCamera();
      setScanHistory([]); // Limpiar historial al cerrar sesión si es necesario
    }
  }, [isSessionActive]);


  return (
    <div className="h-screen bg-slate-950 text-white overflow-hidden flex flex-col font-mono uppercase tracking-wider">
     
      <div className="flex-1 flex items-center justify-center p-4">
        {/* Siempre en modo Monitor/Escritorio */}
        <div className="w-full max-w-6xl aspect-[16/9] bg-slate-900 rounded-[3rem] p-2 border-[12px] border-slate-800 shadow-2xl relative overflow-hidden transition-all duration-500">
         
          <div className="flex flex-col h-full bg-black text-white relative">
            {!isSessionActive && <PatientForm onConfirm={(d) => { setPatientData(generateRandomPatientData(d)); setIsSessionActive(true); }} />}


            {isSessionActive && (
              <div className="flex h-full">
               
                {/* MENU LATERAL */}
                <div className="w-24 border-r border-blue-500/20 bg-slate-950 flex flex-col items-center py-8 gap-8 relative z-50">
                  <button onClick={() => {setActiveTab('scan'); setShowProfile(false);}} className={`flex flex-col items-center gap-1 transition-all ${activeTab === 'scan' ? 'text-blue-500 scale-110' : 'text-slate-600'}`}>
                    <Activity size={24} />
                    <span className="text-[7px] font-black tracking-tighter">ESCANEAR</span>
                  </button>
                  <button onClick={() => {setActiveTab('tests'); setShowProfile(false);}} className={`flex flex-col items-center gap-1 transition-all ${activeTab === 'tests' ? 'text-blue-500 scale-110' : 'text-slate-600'}`}>
                    <Layers size={24} />
                    <span className="text-[7px] font-black tracking-tighter">PRUEBAS</span>
                  </button>
                  <button onClick={() => {setActiveTab('history'); setShowProfile(false);}} className={`flex flex-col items-center gap-1 transition-all ${activeTab === 'history' ? 'text-blue-500 scale-110' : 'text-slate-600'}`}>
                    <History size={24} />
                    <span className="text-[7px] font-black tracking-tighter">HISTORIAL</span>
                  </button>
                  <button onClick={() => {setActiveTab('settings'); setShowProfile(false);}} className={`flex flex-col items-center gap-1 transition-all ${activeTab === 'settings' ? 'text-blue-500 scale-110' : 'text-slate-600'}`}>
                    <Settings size={24} />
                    <span className="text-[7px] font-black tracking-tighter">AJUSTES</span>
                  </button>


                  <div className="mt-auto mb-2 flex flex-col items-center gap-6">
                    <div className="relative">
                      <button onClick={() => setShowProfile(!showProfile)} className={`transition-all ${showProfile ? 'text-blue-400' : 'text-slate-600'}`}>
                        <User size={24} />
                      </button>
                     
                      {showProfile && (
                        <div className="absolute bottom-0 left-24 w-[320px] bg-slate-900 border border-blue-500/30 rounded-3xl p-6 shadow-2xl animate-in slide-in-from-left-4 duration-300 z-[100] backdrop-blur-xl">
                           <div className="flex items-center gap-4 mb-6 border-b border-blue-500/20 pb-4">
                             <div className="w-16 h-16 rounded-2xl bg-slate-800 border border-blue-500/30 overflow-hidden shadow-inner">
                                <img src={patientData.photo} alt="Perfil" className="w-full h-full object-cover" />
                             </div>
                             <div>
                                <h4 className="text-[10px] text-blue-500 font-black tracking-[0.2em]">EXPEDIENTE IA</h4>
                                <span className="text-sm font-black text-white italic tracking-widest">{patientData.id}</span>
                             </div>
                           </div>
                           <div className="space-y-3">
                              <div className="flex items-start gap-3">
                                <CalendarDays size={14} className="text-blue-400 mt-1" />
                                <div className="flex flex-col">
                                  <span className="text-[7px] text-slate-500">NACIMIENTO</span>
                                  <span className="text-[10px] font-bold text-white">{patientData.birthYear}</span>
                                </div>
                              </div>
                              <div className="flex items-start gap-3">
                                <MapPin size={14} className="text-blue-400 mt-1" />
                                <div className="flex flex-col">
                                  <span className="text-[7px] text-slate-500">DIRECCIÓN</span>
                                  <span className="text-[10px] font-bold text-white normal-case">{patientData.address}</span>
                                </div>
                              </div>
                              <div className="flex items-start gap-3">
                                <Stethoscope size={14} className="text-red-400 mt-1" />
                                <div className="flex flex-col">
                                  <span className="text-[7px] text-slate-500">PATOLOGÍAS</span>
                                  <span className="text-[10px] font-bold text-white">{patientData.pathologies}</span>
                                </div>
                              </div>
                              <div className="flex items-start gap-3">
                                <Scissors size={14} className="text-orange-400 mt-1" />
                                <div className="flex flex-col">
                                  <span className="text-[7px] text-slate-500">OPERACIONES</span>
                                  <span className="text-[10px] font-bold text-white">{patientData.operations}</span>
                                </div>
                              </div>
                           </div>
                        </div>
                      )}
                    </div>
                    <button onClick={() => setIsSessionActive(false)} className="text-red-500/40 hover:text-red-500 transition-colors p-2">
                      <Power size={24} />
                    </button>
                  </div>
                </div>


                {/* ÁREA DE CONTENIDO */}
                <div className="flex-1 flex flex-col overflow-hidden bg-gradient-to-br from-black to-slate-950">
                  <div className="flex justify-between items-center px-6 py-4 bg-slate-900 border-b border-blue-500/30">
                    <DiagnosGoLogo mode="mini" />
                    <div className="flex flex-col items-end">
                      <span className="text-[10px] font-black text-blue-400 tracking-widest uppercase">ID: {patientData.id}</span>
                      <div className="flex items-center gap-2">
                        <span className="w-1.5 h-1.5 rounded-full bg-green-500 animate-pulse"></span>
                        <span className="text-[8px] text-slate-500 tracking-[0.2em]">{testType}</span>
                      </div>
                    </div>
                  </div>


                  <div className="flex-1 flex flex-col p-6 gap-6 relative overflow-y-auto">
                    {activeTab === 'scan' && (
                      <>
                        <div className="flex-1 bg-slate-950 rounded-[2.5rem] border border-blue-500/20 relative overflow-hidden shadow-inner group">
                          {cameraActive && !isSimulationMode ? (
                            <video ref={videoRef} autoPlay playsInline className="w-full h-full object-cover opacity-60 brightness-110 grayscale" />
                          ) : (
                            <div className="absolute inset-0 flex flex-col items-center justify-center bg-slate-900/50">
                              <Scan size={80} className="text-blue-500/10 animate-pulse" />
                              <div className="mt-4 px-4 py-2 border border-blue-500/20 rounded-full bg-blue-500/5">
                                <p className="text-[10px] text-blue-400 font-bold tracking-widest uppercase">HARDWARE DE {testType} CONECTADO</p>
                              </div>
                            </div>
                          )}
                         
                          <div className="absolute inset-0 pointer-events-none flex items-center justify-center">
                            <div className="w-48 h-48 border border-blue-500/20 rounded-full flex items-center justify-center animate-pulse">
                              <Crosshair className="text-blue-500/40" size={32} />
                            </div>
                            <div className="absolute top-10 left-10 w-8 h-8 border-t-2 border-l-2 border-blue-500/30"></div>
                            <div className="absolute top-10 right-10 w-8 h-8 border-t-2 border-r-2 border-blue-500/30"></div>
                            <div className="absolute bottom-10 left-10 w-8 h-8 border-b-2 border-l-2 border-blue-500/30"></div>
                            <div className="absolute bottom-10 right-10 w-8 h-8 border-b-2 border-r-2 border-blue-500/30"></div>
                          </div>


                          {isAnalyzing && (
                            <div className="absolute inset-0 bg-blue-900/30 backdrop-blur-xl flex flex-col items-center justify-center z-[60]">
                               <Loader2 className="animate-spin mb-4 text-blue-300" size={64} />
                               <span className="text-4xl font-black italic">{scanProgress}%</span>
                               <span className="text-[10px] tracking-[0.8em] mt-4 animate-pulse">RECONOCIENDO_ANATOMÍA...</span>
                            </div>
                          )}


                          {analysisResult && (
                            <div className="absolute inset-x-4 bottom-4 top-4 bg-slate-950/95 p-6 rounded-[2rem] border-2 border-blue-500/40 animate-in zoom-in-95 duration-500 shadow-2xl flex flex-col md:flex-row gap-6 overflow-y-auto z-50">
                               <div className="flex-1 rounded-2xl border border-blue-500/20 overflow-hidden bg-black flex items-center justify-center relative">
                                  <img src={analysisResult.image} alt="IA Diagnosis" className="w-full h-full object-contain" />
                                  <div className="absolute top-2 left-2 bg-blue-600 px-2 py-0.5 rounded text-[8px] font-black">AI_GEN_VISUAL</div>
                               </div>
                               <div className="flex-1 flex flex-col justify-center">
                                 <div className="flex justify-between items-center mb-2">
                                   <span className="bg-blue-600/20 text-blue-400 text-[8px] px-3 py-1 rounded-full font-black tracking-widest italic">{testType} / {analysisResult.part}</span>
                                   <CheckCircle2 size={24} className="text-green-500" />
                                 </div>
                                 <h2 className="text-2xl font-black italic text-white mb-4 leading-tight border-b border-white/10 pb-4">{analysisResult.diagnosis}</h2>
                                 <div className="space-y-4">
                                   <div className="flex items-center gap-4">
                                     <div className="flex-1 h-1.5 bg-slate-800 rounded-full overflow-hidden">
                                       <div className="h-full bg-green-500" style={{width: analysisResult.confidence}}></div>
                                     </div>
                                     <p className="text-xs text-green-400 font-bold tracking-tighter">{analysisResult.confidence}</p>
                                   </div>
                                   <button onClick={() => setAnalysisResult(null)} className="text-[10px] text-slate-500 hover:text-white underline underline-offset-4 tracking-widest transition-colors uppercase">Realizar nuevo escaneo</button>
                                 </div>
                               </div>
                            </div>
                          )}
                        </div>


                        <div className="flex gap-6 h-28">
                          <div className="flex-1 bg-slate-900/60 rounded-[2rem] p-5 border border-white/5 flex flex-col justify-between overflow-hidden">
                            <div className="flex justify-between items-center mb-2">
                              <span className="text-[8px] text-slate-500 tracking-[0.5em]">HARDWARE_SIGNAL_STRENGTH</span>
                              <span className="text-[8px] text-blue-500 font-bold tracking-widest">{cameraActive ? 'ACTIVO' : 'ESPERA'}</span>
                            </div>
                            <div className="flex gap-1.5 h-full items-end">
                               {[...Array(40)].map((_, i) => (
                                 <div key={i} className="flex-1 bg-blue-500/30 rounded-full" style={{ height: cameraActive ? `${20 + Math.random()*80}%` : '5%', transition: 'height 0.4s ease' }}></div>
                               ))}
                            </div>
                          </div>
                          <button onClick={handleStartAnalysis} className="w-1/3 bg-blue-600 rounded-[2rem] font-black text-xs tracking-[0.2em] hover:bg-blue-500 active:scale-95 transition-all shadow-2xl shadow-blue-900/40 border-t border-white/20 group flex flex-col items-center justify-center gap-1">
                            <Camera size={24} className="mb-1" />
                            {cameraActive ? 'ESCANEAR' : 'CONECTAR'}
                          </button>
                        </div>
                      </>
                    )}


                    {activeTab === 'tests' && (
                      <div className="grid grid-cols-1 md:grid-cols-3 gap-6 animate-in fade-in slide-in-from-bottom-4">
                        {[
                          { id: 'ECOGRAFÍA', icon: Waves, label: 'ECOGRAFÍA', desc: 'Diagnóstico por ultrasonido para tejidos blandos y órganos.' },
                          { id: 'RADIOGRAFÍA', icon: Zap, label: 'RADIOGRAFÍA', desc: 'Exploración por rayos X de alta precisión para sistemas óseos.' },
                          { id: 'RESONANCIA', icon: Magnet, label: 'RESONANCIA', desc: 'Imagenología magnética avanzada para neuro y estructuras complejas.' }
                        ].map((test) => (
                          <div key={test.id} onClick={() => { setTestType(test.id); setActiveTab('scan'); }} className={`p-8 rounded-[2.5rem] border-2 cursor-pointer transition-all flex flex-col items-center gap-6 text-center group ${testType === test.id ? 'bg-blue-600/20 border-blue-500 shadow-lg shadow-blue-500/10' : 'bg-slate-900/40 border-slate-800 hover:border-blue-500/40'}`}>
                            <div className={`w-20 h-20 rounded-full flex items-center justify-center ${testType === test.id ? 'bg-blue-500 text-white' : 'bg-slate-800 text-slate-500 group-hover:text-blue-400'}`}>
                              <test.icon size={40} />
                            </div>
                            <div className="space-y-2">
                              <h3 className="font-black italic text-xl tracking-wider">{test.label}</h3>
                              <p className="text-[10px] text-slate-500 leading-relaxed font-sans normal-case px-4">{test.desc}</p>
                            </div>
                            {testType === test.id && <span className="text-[10px] bg-blue-600 px-6 py-1.5 rounded-full font-black tracking-widest shadow-lg">ACTIVA</span>}
                          </div>
                        ))}
                      </div>
                    )}


                    {activeTab === 'history' && (
                      <div className="flex flex-col gap-6 animate-in fade-in h-full overflow-hidden">
                        <div className="flex items-center justify-between border-b border-blue-500/20 pb-4">
                          <h2 className="text-xl font-black italic flex items-center gap-3">
                             <Clock className="text-blue-500" /> HISTORIAL DE SESIÓN
                          </h2>
                          <span className="text-[10px] text-slate-500 tracking-[0.2em]">PACIENTE: {patientData.id}</span>
                        </div>
                       
                        <div className="flex-1 overflow-y-auto pr-2 space-y-4">
                          {scanHistory.length === 0 ? (
                            <div className="flex flex-col items-center justify-center h-full opacity-20 gap-6">
                              <div className="w-24 h-24 border-2 border-dashed border-slate-600 rounded-full flex items-center justify-center">
                                <ClipboardList size={48} />
                              </div>
                              <p className="text-xs tracking-[0.5em] font-black uppercase">Sin registros en esta sesión</p>
                            </div>
                          ) : (
                            scanHistory.map((item) => (
                              <div key={item.id} className="bg-slate-900/40 border border-white/5 rounded-3xl p-6 flex gap-6 items-center hover:border-blue-500/30 transition-all group">
                                <div className="w-24 h-24 bg-black rounded-xl overflow-hidden border border-slate-800 flex-shrink-0">
                                   <img src={item.image} alt="Historial" className="w-full h-full object-cover" />
                                </div>
                                <div className="flex-1">
                                   <div className="flex justify-between items-start mb-2">
                                      <div className="flex items-center gap-2">
                                        <span className="text-[8px] bg-blue-600/30 text-blue-400 px-2 py-0.5 rounded font-black">{item.type}</span>
                                        <span className="text-[8px] bg-slate-800 text-slate-400 px-2 py-0.5 rounded font-black">{item.part}</span>
                                      </div>
                                      <span className="text-[10px] text-slate-500 font-mono italic">{item.timestamp}</span>
                                   </div>
                                   <h3 className="text-sm font-black italic text-white mb-2">{item.diagnosis}</h3>
                                   <div className="flex items-center gap-2">
                                      <Activity size={12} className="text-green-500" />
                                      <span className="text-[10px] text-green-500 font-bold">Fiabilidad IA: {item.confidence}</span>
                                   </div>
                                </div>
                                <button onClick={() => { setAnalysisResult(item); setActiveTab('scan'); }} className="p-3 rounded-full bg-slate-800 text-slate-500 hover:text-blue-400 hover:bg-slate-700 transition-all opacity-0 group-hover:opacity-100">
                                   <FileText size={20} />
                                </button>
                              </div>
                            ))
                          )}
                        </div>
                      </div>
                    )}


                    {activeTab === 'settings' && (
                      <div className="max-w-2xl mx-auto w-full bg-slate-900/40 p-10 rounded-[3rem] border border-white/5 space-y-10 animate-in fade-in">
                        <div className="flex items-center gap-4 border-b border-blue-500/20 pb-6">
                           <Sliders className="text-blue-400" />
                           <h2 className="text-2xl font-black italic uppercase">Configuración de IA</h2>
                        </div>
                        <div className="space-y-8">
                          <div className="space-y-4">
                            <div className="flex justify-between items-center">
                              <span className="text-xs font-bold text-slate-400 tracking-[0.2em]">UMBRAL DE CONFIANZA</span>
                              <span className="text-blue-400 font-black text-2xl">{reliabilityLevel}%</span>
                            </div>
                            <input type="range" min="70" max="99" value={reliabilityLevel} onChange={(e) => setReliabilityLevel(parseInt(e.target.value))} className="w-full h-2 bg-slate-800 rounded-lg appearance-none cursor-pointer accent-blue-500" />
                          </div>
                        </div>
                        <button onClick={stopCamera} className="w-full flex justify-between items-center p-5 bg-red-500/5 border border-red-500/10 rounded-2xl hover:bg-red-500/10 transition-colors text-red-500 group uppercase">
                          <span className="text-xs font-black tracking-widest">Apagar Hardware de Captura</span>
                          <RefreshCw size={18} className="group-active:animate-spin" />
                        </button>
                      </div>
                    )}
                  </div>
                </div>


              </div>
            )}
          </div>
        </div>
      </div>


      <style dangerouslySetInnerHTML={{ __html: `
        ::-webkit-scrollbar { width: 4px; }
        ::-webkit-scrollbar-track { background: transparent; }
        ::-webkit-scrollbar-thumb { background: #1e293b; border-radius: 10px; }
        ::-webkit-scrollbar-thumb:hover { background: #3b82f6; }
        ::-webkit-calendar-picker-indicator { filter: invert(1); }
        input[type='range']::-webkit-slider-thumb {in
          -webkit-appearance: none; appearance: none;
          width: 24px; height: 24px;
          background: #3b82f6; cursor: pointer;
          border-radius: 50%; border: 4px solid #000;
        }
      `}} />
    </div>
  );
}


