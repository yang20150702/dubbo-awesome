# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.381 ops/ms
# Warmup Iteration   2: 5.635 ops/ms
# Warmup Iteration   3: 9.227 ops/ms
Iteration   1: 9.558 ops/ms
Iteration   2: 10.086 ops/ms
Iteration   3: 9.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.802 ±(99.9%) 4.866 ops/ms [Average]
  (min, avg, max) = (9.558, 9.802, 10.086), stdev = 0.267
  CI (99.9%): [4.936, 14.667] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.386 ops/ms
# Warmup Iteration   2: 9.253 ops/ms
# Warmup Iteration   3: 10.415 ops/ms
Iteration   1: 10.746 ops/ms
Iteration   2: 10.371 ops/ms
Iteration   3: 10.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.469 ±(99.9%) 4.452 ops/ms [Average]
  (min, avg, max) = (10.288, 10.469, 10.746), stdev = 0.244
  CI (99.9%): [6.017, 14.921] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.149 ops/ms
# Warmup Iteration   2: 8.725 ops/ms
# Warmup Iteration   3: 9.973 ops/ms
Iteration   1: 9.788 ops/ms
Iteration   2: 10.154 ops/ms
Iteration   3: 10.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.024 ±(99.9%) 3.735 ops/ms [Average]
  (min, avg, max) = (9.788, 10.024, 10.154), stdev = 0.205
  CI (99.9%): [6.289, 13.758] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.447 ops/ms
# Warmup Iteration   2: 8.139 ops/ms
# Warmup Iteration   3: 8.278 ops/ms
Iteration   1: 8.502 ops/ms
Iteration   2: 8.700 ops/ms
Iteration   3: 8.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.595 ±(99.9%) 1.811 ops/ms [Average]
  (min, avg, max) = (8.502, 8.595, 8.700), stdev = 0.099
  CI (99.9%): [6.783, 10.406] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.203 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.003 ms/op
Iteration   1: 3.196 ±(99.9%) 0.004 ms/op
Iteration   2: 3.311 ±(99.9%) 0.007 ms/op
Iteration   3: 3.009 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.172 ±(99.9%) 2.785 ms/op [Average]
  (min, avg, max) = (3.009, 3.172, 3.311), stdev = 0.153
  CI (99.9%): [0.387, 5.957] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.672 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.434 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.005 ms/op
Iteration   1: 3.233 ±(99.9%) 0.007 ms/op
Iteration   2: 3.181 ±(99.9%) 0.005 ms/op
Iteration   3: 3.012 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.142 ±(99.9%) 2.110 ms/op [Average]
  (min, avg, max) = (3.012, 3.142, 3.233), stdev = 0.116
  CI (99.9%): [1.032, 5.251] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.906 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.002 ms/op
Iteration   1: 3.177 ±(99.9%) 0.002 ms/op
Iteration   2: 3.091 ±(99.9%) 0.002 ms/op
Iteration   3: 3.145 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.138 ±(99.9%) 0.795 ms/op [Average]
  (min, avg, max) = (3.091, 3.138, 3.177), stdev = 0.044
  CI (99.9%): [2.342, 3.933] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.732 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.710 ±(99.9%) 0.006 ms/op
Iteration   1: 3.657 ±(99.9%) 0.009 ms/op
Iteration   2: 3.675 ±(99.9%) 0.007 ms/op
Iteration   3: 3.827 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.720 ±(99.9%) 1.703 ms/op [Average]
  (min, avg, max) = (3.657, 3.720, 3.827), stdev = 0.093
  CI (99.9%): [2.017, 5.423] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.852 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.858 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.008 ms/op
Iteration   1: 3.228 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  11.321 ms/op
                 createUser·p0.9999: 32.178 ms/op
                 createUser·p1.00:   32.702 ms/op

Iteration   2: 3.137 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   5.046 ms/op
                 createUser·p0.999:  18.875 ms/op
                 createUser·p0.9999: 22.112 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   3: 3.270 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.729 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  17.793 ms/op
                 createUser·p0.9999: 24.735 ms/op
                 createUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298919
  mean =      3.211 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16462 
    [ 2.500,  5.000) = 277543 
    [ 5.000,  7.500) = 4034 
    [ 7.500, 10.000) = 414 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     18.254 ms/op
     p(99.9900) =     30.576 ms/op
     p(99.9990) =     32.443 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.174 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 3.340 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
Iteration   1: 3.180 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   4.059 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  11.704 ms/op
                 existUser·p0.9999: 19.691 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   2: 3.097 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.436 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  17.826 ms/op
                 existUser·p0.9999: 21.845 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   3: 3.099 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.289 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  9.350 ms/op
                 existUser·p0.9999: 20.382 ms/op
                 existUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307303
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24530 
    [ 2.500,  5.000) = 276912 
    [ 5.000,  7.500) = 5219 
    [ 7.500, 10.000) = 242 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     14.495 ms/op
     p(99.9900) =     21.406 ms/op
     p(99.9990) =     22.624 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.071 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.009 ms/op
Iteration   1: 3.240 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  18.317 ms/op
                 getUser·p0.9999: 23.101 ms/op
                 getUser·p1.00:   23.527 ms/op

Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.543 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  10.780 ms/op
                 getUser·p0.9999: 24.112 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   3: 3.242 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.397 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  10.393 ms/op
                 getUser·p0.9999: 20.452 ms/op
                 getUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298764
  mean =      3.210 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12412 
    [ 2.500,  5.000) = 279300 
    [ 5.000,  7.500) = 6076 
    [ 7.500, 10.000) = 575 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     17.014 ms/op
     p(99.9900) =     23.466 ms/op
     p(99.9990) =     24.708 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.437 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.011 ms/op
Iteration   1: 3.753 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  14.568 ms/op
                 listUser·p0.9999: 26.427 ms/op
                 listUser·p1.00:   26.804 ms/op

Iteration   2: 3.677 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.905 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  13.664 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   3: 3.640 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   3.760 ms/op
                 listUser·p0.95:   4.182 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  12.019 ms/op
                 listUser·p0.9999: 14.373 ms/op
                 listUser·p1.00:   14.664 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259951
  mean =      3.689 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 252970 
    [ 5.000,  7.500) = 5163 
    [ 7.500, 10.000) = 1089 
    [10.000, 12.500) = 320 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.905 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     13.732 ms/op
     p(99.9900) =     24.970 ms/op
     p(99.9990) =     26.771 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.802 ± 4.866  ops/ms
ClientPb.existUser                       thrpt       3  10.469 ± 4.452  ops/ms
ClientPb.getUser                         thrpt       3  10.024 ± 3.735  ops/ms
ClientPb.listUser                        thrpt       3   8.595 ± 1.811  ops/ms
ClientPb.createUser                       avgt       3   3.172 ± 2.785   ms/op
ClientPb.existUser                        avgt       3   3.142 ± 2.110   ms/op
ClientPb.getUser                          avgt       3   3.138 ± 0.795   ms/op
ClientPb.listUser                         avgt       3   3.720 ± 1.703   ms/op
ClientPb.createUser                     sample  298919   3.211 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.094           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.531           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.254           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.576           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.702           ms/op
ClientPb.existUser                      sample  307303   3.125 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.071           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.367           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.116           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.495           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.406           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.970           ms/op
ClientPb.getUser                        sample  298764   3.210 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.659           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.543           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.014           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.466           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.002           ms/op
ClientPb.listUser                       sample  259951   3.689 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.905           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.568           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.947           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.732           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.970           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.804           ms/op
