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
# Warmup Iteration   1: 4.097 ops/ms
# Warmup Iteration   2: 9.079 ops/ms
# Warmup Iteration   3: 9.924 ops/ms
Iteration   1: 10.275 ops/ms
Iteration   2: 10.659 ops/ms
Iteration   3: 10.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.460 ±(99.9%) 3.515 ops/ms [Average]
  (min, avg, max) = (10.275, 10.460, 10.659), stdev = 0.193
  CI (99.9%): [6.945, 13.975] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.159 ops/ms
# Warmup Iteration   2: 10.404 ops/ms
# Warmup Iteration   3: 10.759 ops/ms
Iteration   1: 10.970 ops/ms
Iteration   2: 10.984 ops/ms
Iteration   3: 10.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.984 ±(99.9%) 0.249 ops/ms [Average]
  (min, avg, max) = (10.970, 10.984, 10.997), stdev = 0.014
  CI (99.9%): [10.735, 11.233] (assumes normal distribution)


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
# Warmup Iteration   1: 6.967 ops/ms
# Warmup Iteration   2: 9.982 ops/ms
# Warmup Iteration   3: 10.539 ops/ms
Iteration   1: 10.638 ops/ms
Iteration   2: 10.483 ops/ms
Iteration   3: 10.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.557 ±(99.9%) 1.420 ops/ms [Average]
  (min, avg, max) = (10.483, 10.557, 10.638), stdev = 0.078
  CI (99.9%): [9.137, 11.977] (assumes normal distribution)


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
# Warmup Iteration   1: 6.469 ops/ms
# Warmup Iteration   2: 7.648 ops/ms
# Warmup Iteration   3: 8.081 ops/ms
Iteration   1: 8.038 ops/ms
Iteration   2: 8.126 ops/ms
Iteration   3: 8.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.061 ±(99.9%) 1.042 ops/ms [Average]
  (min, avg, max) = (8.019, 8.061, 8.126), stdev = 0.057
  CI (99.9%): [7.018, 9.103] (assumes normal distribution)


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
# Warmup Iteration   1: 4.312 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.003 ms/op
Iteration   1: 3.027 ±(99.9%) 0.003 ms/op
Iteration   2: 3.015 ±(99.9%) 0.003 ms/op
Iteration   3: 3.034 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.025 ±(99.9%) 0.171 ms/op [Average]
  (min, avg, max) = (3.015, 3.025, 3.034), stdev = 0.009
  CI (99.9%): [2.854, 3.197] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.971 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.972 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.915 ±(99.9%) 0.001 ms/op
Iteration   1: 2.882 ±(99.9%) 0.003 ms/op
Iteration   2: 2.898 ±(99.9%) 0.002 ms/op
Iteration   3: 2.913 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.898 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (2.882, 2.898, 2.913), stdev = 0.016
  CI (99.9%): [2.610, 3.186] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.145 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.002 ms/op
Iteration   1: 2.981 ±(99.9%) 0.004 ms/op
Iteration   2: 3.036 ±(99.9%) 0.002 ms/op
Iteration   3: 3.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.029 ±(99.9%) 0.832 ms/op [Average]
  (min, avg, max) = (2.981, 3.029, 3.072), stdev = 0.046
  CI (99.9%): [2.197, 3.862] (assumes normal distribution)


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
# Warmup Iteration   1: 5.439 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.039 ms/op
Iteration   1: 4.004 ±(99.9%) 0.012 ms/op
Iteration   2: 3.882 ±(99.9%) 0.018 ms/op
Iteration   3: 3.903 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.930 ±(99.9%) 1.189 ms/op [Average]
  (min, avg, max) = (3.882, 3.930, 4.004), stdev = 0.065
  CI (99.9%): [2.741, 5.119] (assumes normal distribution)


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
# Warmup Iteration   1: 4.227 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.006 ms/op
Iteration   1: 3.051 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  7.234 ms/op
                 createUser·p0.9999: 13.156 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   2: 3.055 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  7.435 ms/op
                 createUser·p0.9999: 15.049 ms/op
                 createUser·p1.00:   15.270 ms/op

Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  8.266 ms/op
                 createUser·p0.9999: 18.413 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315114
  mean =      3.047 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 399 
    [ 1.250,  2.500) = 12990 
    [ 2.500,  3.750) = 288938 
    [ 3.750,  5.000) = 11752 
    [ 5.000,  6.250) = 391 
    [ 6.250,  7.500) = 291 
    [ 7.500,  8.750) = 127 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      8.004 ms/op
     p(99.9900) =     17.217 ms/op
     p(99.9990) =     18.897 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.899 ±(99.9%) 0.006 ms/op
Iteration   1: 2.906 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.495 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   19.366 ms/op

Iteration   2: 2.881 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.512 ms/op
                 existUser·p0.9999: 14.251 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   3: 2.900 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  8.540 ms/op
                 existUser·p0.9999: 26.803 ms/op
                 existUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331471
  mean =      2.896 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43060 
    [ 2.500,  5.000) = 287310 
    [ 5.000,  7.500) = 843 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      6.611 ms/op
     p(99.9900) =     21.032 ms/op
     p(99.9990) =     26.958 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 4.176 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
Iteration   1: 3.045 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  7.160 ms/op
                 getUser·p0.9999: 17.285 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  7.823 ms/op
                 getUser·p0.9999: 18.285 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  7.241 ms/op
                 getUser·p0.9999: 21.430 ms/op
                 getUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315828
  mean =      3.037 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14527 
    [ 2.500,  5.000) = 300273 
    [ 5.000,  7.500) = 695 
    [ 7.500, 10.000) = 173 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      7.589 ms/op
     p(99.9900) =     20.343 ms/op
     p(99.9990) =     21.627 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 5.323 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.011 ms/op
Iteration   1: 3.937 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.549 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  14.414 ms/op
                 listUser·p0.9999: 16.562 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   2: 3.900 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.778 ms/op
                 listUser·p0.9999: 23.704 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   3: 3.941 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  14.954 ms/op
                 listUser·p0.9999: 19.289 ms/op
                 listUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244422
  mean =      3.926 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2287 
    [ 2.500,  5.000) = 221068 
    [ 5.000,  7.500) = 19584 
    [ 7.500, 10.000) = 1017 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     15.090 ms/op
     p(99.9900) =     21.743 ms/op
     p(99.9990) =     24.103 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.460 ± 3.515  ops/ms
ClientGrpc.existUser                       thrpt       3  10.984 ± 0.249  ops/ms
ClientGrpc.getUser                         thrpt       3  10.557 ± 1.420  ops/ms
ClientGrpc.listUser                        thrpt       3   8.061 ± 1.042  ops/ms
ClientGrpc.createUser                       avgt       3   3.025 ± 0.171   ms/op
ClientGrpc.existUser                        avgt       3   2.898 ± 0.288   ms/op
ClientGrpc.getUser                          avgt       3   3.029 ± 0.832   ms/op
ClientGrpc.listUser                         avgt       3   3.930 ± 1.189   ms/op
ClientGrpc.createUser                     sample  315114   3.047 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.728           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.004           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.217           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.038           ms/op
ClientGrpc.existUser                      sample  331471   2.896 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.667           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.611           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.032           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.296           ms/op
ClientGrpc.getUser                        sample  315828   3.037 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.821           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.174           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.589           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.343           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.725           ms/op
ClientGrpc.listUser                       sample  244422   3.926 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.873           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.090           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.743           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.216           ms/op
