# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.399 ops/ms
# Warmup Iteration   2: 12.323 ops/ms
# Warmup Iteration   3: 12.683 ops/ms
Iteration   1: 12.823 ops/ms
Iteration   2: 12.931 ops/ms
Iteration   3: 12.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.883 ±(99.9%) 0.995 ops/ms [Average]
  (min, avg, max) = (12.823, 12.883, 12.931), stdev = 0.055
  CI (99.9%): [11.888, 13.878] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.394 ops/ms
# Warmup Iteration   2: 12.892 ops/ms
# Warmup Iteration   3: 13.182 ops/ms
Iteration   1: 13.366 ops/ms
Iteration   2: 13.370 ops/ms
Iteration   3: 13.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.317 ±(99.9%) 1.631 ops/ms [Average]
  (min, avg, max) = (13.213, 13.317, 13.370), stdev = 0.089
  CI (99.9%): [11.686, 14.947] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.990 ops/ms
# Warmup Iteration   2: 12.601 ops/ms
# Warmup Iteration   3: 12.857 ops/ms
Iteration   1: 13.067 ops/ms
Iteration   2: 13.001 ops/ms
Iteration   3: 13.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.044 ±(99.9%) 0.680 ops/ms [Average]
  (min, avg, max) = (13.001, 13.044, 13.067), stdev = 0.037
  CI (99.9%): [12.364, 13.723] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.861 ops/ms
# Warmup Iteration   2: 10.586 ops/ms
# Warmup Iteration   3: 10.751 ops/ms
Iteration   1: 10.771 ops/ms
Iteration   2: 10.770 ops/ms
Iteration   3: 10.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.765 ±(99.9%) 0.195 ops/ms [Average]
  (min, avg, max) = (10.752, 10.765, 10.771), stdev = 0.011
  CI (99.9%): [10.569, 10.960] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.052 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.003 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.486 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (2.455, 2.486, 2.502), stdev = 0.027
  CI (99.9%): [1.990, 2.982] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.595 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
Iteration   1: 2.427 ±(99.9%) 0.005 ms/op
Iteration   2: 2.423 ±(99.9%) 0.003 ms/op
Iteration   3: 2.431 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.427 ±(99.9%) 0.078 ms/op [Average]
  (min, avg, max) = (2.423, 2.427, 2.431), stdev = 0.004
  CI (99.9%): [2.349, 2.506] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.838 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.003 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.462 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.462 ±(99.9%) 0.015 ms/op [Average]
  (min, avg, max) = (2.462, 2.462, 2.463), stdev = 0.001
  CI (99.9%): [2.447, 2.477] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.566 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.005 ms/op
Iteration   1: 2.954 ±(99.9%) 0.006 ms/op
Iteration   2: 2.911 ±(99.9%) 0.006 ms/op
Iteration   3: 2.947 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.937 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (2.911, 2.937, 2.954), stdev = 0.023
  CI (99.9%): [2.518, 3.357] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.000 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.006 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.981 ms/op
                 createUser·p0.999:  8.126 ms/op
                 createUser·p0.9999: 13.436 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  9.699 ms/op
                 createUser·p0.9999: 12.679 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  8.465 ms/op
                 createUser·p0.9999: 11.305 ms/op
                 createUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384455
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 187700 
    [ 2.500,  3.750) = 192398 
    [ 3.750,  5.000) = 3325 
    [ 5.000,  6.250) = 482 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 142 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     12.976 ms/op
     p(99.9990) =     13.702 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.923 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.424 ±(99.9%) 0.005 ms/op
Iteration   1: 2.429 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  6.947 ms/op
                 existUser·p0.9999: 16.594 ms/op
                 existUser·p1.00:   17.105 ms/op

Iteration   2: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  5.739 ms/op
                 existUser·p0.9999: 13.808 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   3: 2.408 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  7.595 ms/op
                 existUser·p0.9999: 10.797 ms/op
                 existUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396842
  mean =      2.417 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 200285 
    [ 2.500,  3.750) = 193469 
    [ 3.750,  5.000) = 2236 
    [ 5.000,  6.250) = 308 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 116 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =      7.220 ms/op
     p(99.9900) =     15.805 ms/op
     p(99.9990) =     16.942 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.892 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  7.417 ms/op
                 getUser·p0.9999: 13.683 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  5.782 ms/op
                 getUser·p0.9999: 13.287 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.654 ms/op
                 getUser·p0.999:  8.192 ms/op
                 getUser·p0.9999: 11.747 ms/op
                 getUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388722
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 195169 
    [ 2.500,  3.750) = 189566 
    [ 3.750,  5.000) = 3242 
    [ 5.000,  6.250) = 278 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      8.011 ms/op
     p(99.9900) =     13.224 ms/op
     p(99.9990) =     13.928 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.555 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.009 ms/op
Iteration   1: 2.969 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.820 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 11.059 ms/op
                 listUser·p1.00:   12.730 ms/op

Iteration   2: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.839 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.781 ms/op
                 listUser·p0.9999: 11.420 ms/op
                 listUser·p1.00:   11.960 ms/op

Iteration   3: 2.955 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 11.652 ms/op
                 listUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323677
  mean =      2.963 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 168 
    [ 1.250,  2.500) = 100432 
    [ 2.500,  3.750) = 186445 
    [ 3.750,  5.000) = 30085 
    [ 5.000,  6.250) = 5394 
    [ 6.250,  7.500) = 517 
    [ 7.500,  8.750) = 190 
    [ 8.750, 10.000) = 231 
    [10.000, 11.250) = 169 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     11.397 ms/op
     p(99.9990) =     12.023 ms/op
     p(99.9999) =     12.730 ms/op
    p(100.0000) =     12.730 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.883 ± 0.995  ops/ms
ClientPb.existUser                       thrpt       3  13.317 ± 1.631  ops/ms
ClientPb.getUser                         thrpt       3  13.044 ± 0.680  ops/ms
ClientPb.listUser                        thrpt       3  10.765 ± 0.195  ops/ms
ClientPb.createUser                       avgt       3   2.486 ± 0.496   ms/op
ClientPb.existUser                        avgt       3   2.427 ± 0.078   ms/op
ClientPb.getUser                          avgt       3   2.462 ± 0.015   ms/op
ClientPb.listUser                         avgt       3   2.937 ± 0.419   ms/op
ClientPb.createUser                     sample  384455   2.495 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.802           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.487           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.976           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.910           ms/op
ClientPb.existUser                      sample  396842   2.417 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.694           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.220           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.805           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.105           ms/op
ClientPb.getUser                        sample  388722   2.467 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.933           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.011           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.224           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.205           ms/op
ClientPb.listUser                       sample  323677   2.963 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.820           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.404           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.397           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.730           ms/op
