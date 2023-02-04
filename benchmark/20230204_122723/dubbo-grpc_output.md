# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.727 ops/ms
# Warmup Iteration   2: 9.174 ops/ms
# Warmup Iteration   3: 9.887 ops/ms
Iteration   1: 9.966 ops/ms
Iteration   2: 10.154 ops/ms
Iteration   3: 9.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.037 ±(99.9%) 1.867 ops/ms [Average]
  (min, avg, max) = (9.966, 10.037, 10.154), stdev = 0.102
  CI (99.9%): [8.169, 11.904] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.529 ops/ms
# Warmup Iteration   2: 10.243 ops/ms
# Warmup Iteration   3: 10.528 ops/ms
Iteration   1: 10.387 ops/ms
Iteration   2: 10.601 ops/ms
Iteration   3: 10.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.531 ±(99.9%) 2.273 ops/ms [Average]
  (min, avg, max) = (10.387, 10.531, 10.604), stdev = 0.125
  CI (99.9%): [8.257, 12.804] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.698 ops/ms
# Warmup Iteration   2: 9.774 ops/ms
# Warmup Iteration   3: 10.200 ops/ms
Iteration   1: 10.167 ops/ms
Iteration   2: 10.174 ops/ms
Iteration   3: 10.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.128 ±(99.9%) 1.332 ops/ms [Average]
  (min, avg, max) = (10.044, 10.128, 10.174), stdev = 0.073
  CI (99.9%): [8.796, 11.460] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.295 ops/ms
# Warmup Iteration   2: 7.688 ops/ms
# Warmup Iteration   3: 7.761 ops/ms
Iteration   1: 8.029 ops/ms
Iteration   2: 8.033 ops/ms
Iteration   3: 7.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.971 ±(99.9%) 1.900 ops/ms [Average]
  (min, avg, max) = (7.850, 7.971, 8.033), stdev = 0.104
  CI (99.9%): [6.070, 9.871] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.190 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.002 ms/op
Iteration   1: 3.286 ±(99.9%) 0.002 ms/op
Iteration   2: 3.282 ±(99.9%) 0.001 ms/op
Iteration   3: 3.153 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.240 ±(99.9%) 1.382 ms/op [Average]
  (min, avg, max) = (3.153, 3.240, 3.286), stdev = 0.076
  CI (99.9%): [1.858, 4.623] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.939 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.001 ms/op
Iteration   1: 3.007 ±(99.9%) 0.002 ms/op
Iteration   2: 3.016 ±(99.9%) 0.002 ms/op
Iteration   3: 3.003 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.008 ±(99.9%) 0.118 ms/op [Average]
  (min, avg, max) = (3.003, 3.008, 3.016), stdev = 0.006
  CI (99.9%): [2.891, 3.126] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.265 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.004 ms/op
Iteration   1: 3.200 ±(99.9%) 0.003 ms/op
Iteration   2: 3.248 ±(99.9%) 0.002 ms/op
Iteration   3: 3.179 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.209 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.179, 3.209, 3.248), stdev = 0.035
  CI (99.9%): [2.565, 3.852] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.353 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.241 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.021 ms/op
Iteration   1: 4.081 ±(99.9%) 0.013 ms/op
Iteration   2: 4.084 ±(99.9%) 0.032 ms/op
Iteration   3: 3.999 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.055 ±(99.9%) 0.885 ms/op [Average]
  (min, avg, max) = (3.999, 4.055, 4.084), stdev = 0.048
  CI (99.9%): [3.170, 4.939] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.432 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.008 ms/op
Iteration   1: 3.254 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  9.557 ms/op
                 createUser·p0.9999: 14.601 ms/op
                 createUser·p1.00:   16.941 ms/op

Iteration   2: 3.214 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.714 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  8.330 ms/op
                 createUser·p0.9999: 17.501 ms/op
                 createUser·p1.00:   17.957 ms/op

Iteration   3: 3.303 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  10.755 ms/op
                 createUser·p0.9999: 20.425 ms/op
                 createUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 294707
  mean =      3.257 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18171 
    [ 2.500,  5.000) = 275030 
    [ 5.000,  7.500) = 1042 
    [ 7.500, 10.000) = 181 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      9.468 ms/op
     p(99.9900) =     20.006 ms/op
     p(99.9990) =     20.549 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.007 ms/op
Iteration   1: 3.123 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  6.583 ms/op
                 existUser·p0.9999: 13.943 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   2: 3.001 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.438 ms/op
                 existUser·p0.9999: 22.948 ms/op
                 existUser·p1.00:   23.331 ms/op

Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  5.721 ms/op
                 existUser·p0.9999: 16.379 ms/op
                 existUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312473
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29909 
    [ 2.500,  5.000) = 281654 
    [ 5.000,  7.500) = 715 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      6.550 ms/op
     p(99.9900) =     21.086 ms/op
     p(99.9990) =     23.294 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.173 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.006 ms/op
Iteration   1: 3.153 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  6.716 ms/op
                 getUser·p0.9999: 18.149 ms/op
                 getUser·p1.00:   18.645 ms/op

Iteration   2: 3.117 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.803 ms/op
                 getUser·p0.9999: 13.255 ms/op
                 getUser·p1.00:   13.353 ms/op

Iteration   3: 3.189 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.615 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.521 ms/op
                 getUser·p0.9999: 17.039 ms/op
                 getUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304464
  mean =      3.153 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 517 
    [ 1.250,  2.500) = 22543 
    [ 2.500,  3.750) = 242650 
    [ 3.750,  5.000) = 37860 
    [ 5.000,  6.250) = 403 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      6.927 ms/op
     p(99.9900) =     17.498 ms/op
     p(99.9990) =     18.445 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.415 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.011 ms/op
Iteration   1: 3.993 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.740 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   6.927 ms/op
                 listUser·p0.999:  13.058 ms/op
                 listUser·p0.9999: 15.580 ms/op
                 listUser·p1.00:   16.679 ms/op

Iteration   2: 3.946 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  15.264 ms/op
                 listUser·p0.9999: 30.364 ms/op
                 listUser·p1.00:   33.948 ms/op

Iteration   3: 3.986 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  14.709 ms/op
                 listUser·p0.9999: 16.482 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241556
  mean =      3.975 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3392 
    [ 2.500,  5.000) = 215376 
    [ 5.000,  7.500) = 21690 
    [ 7.500, 10.000) = 647 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     14.505 ms/op
     p(99.9900) =     28.138 ms/op
     p(99.9990) =     31.348 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.037 ± 1.867  ops/ms
ClientGrpc.existUser                       thrpt       3  10.531 ± 2.273  ops/ms
ClientGrpc.getUser                         thrpt       3  10.128 ± 1.332  ops/ms
ClientGrpc.listUser                        thrpt       3   7.971 ± 1.900  ops/ms
ClientGrpc.createUser                       avgt       3   3.240 ± 1.382   ms/op
ClientGrpc.existUser                        avgt       3   3.008 ± 0.118   ms/op
ClientGrpc.getUser                          avgt       3   3.209 ± 0.643   ms/op
ClientGrpc.listUser                         avgt       3   4.055 ± 0.885   ms/op
ClientGrpc.createUser                     sample  294707   3.257 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.686           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.224           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.182           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.468           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.006           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.677           ms/op
ClientGrpc.existUser                      sample  312473   3.073 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.716           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.043           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.949           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.550           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.086           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.331           ms/op
ClientGrpc.getUser                        sample  304464   3.153 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.615           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.998           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.927           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.498           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.645           ms/op
ClientGrpc.listUser                       sample  241556   3.975 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.740           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.505           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.138           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.948           ms/op
