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
# Warmup Iteration   1: 2.321 ops/ms
# Warmup Iteration   2: 5.945 ops/ms
# Warmup Iteration   3: 8.454 ops/ms
Iteration   1: 9.356 ops/ms
Iteration   2: 9.261 ops/ms
Iteration   3: 9.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.227 ±(99.9%) 2.711 ops/ms [Average]
  (min, avg, max) = (9.064, 9.227, 9.356), stdev = 0.149
  CI (99.9%): [6.516, 11.938] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.688 ops/ms
# Warmup Iteration   2: 8.945 ops/ms
# Warmup Iteration   3: 9.651 ops/ms
Iteration   1: 9.228 ops/ms
Iteration   2: 9.510 ops/ms
Iteration   3: 9.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.467 ±(99.9%) 4.020 ops/ms [Average]
  (min, avg, max) = (9.228, 9.467, 9.662), stdev = 0.220
  CI (99.9%): [5.447, 13.487] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.952 ops/ms
# Warmup Iteration   2: 8.026 ops/ms
# Warmup Iteration   3: 9.052 ops/ms
Iteration   1: 9.248 ops/ms
Iteration   2: 9.478 ops/ms
Iteration   3: 9.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.403 ±(99.9%) 2.456 ops/ms [Average]
  (min, avg, max) = (9.248, 9.403, 9.484), stdev = 0.135
  CI (99.9%): [6.947, 11.860] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.690 ops/ms
# Warmup Iteration   2: 7.343 ops/ms
# Warmup Iteration   3: 7.883 ops/ms
Iteration   1: 8.141 ops/ms
Iteration   2: 8.189 ops/ms
Iteration   3: 8.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.157 ±(99.9%) 0.517 ops/ms [Average]
  (min, avg, max) = (8.139, 8.157, 8.189), stdev = 0.028
  CI (99.9%): [7.639, 8.674] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.720 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.735 ±(99.9%) 0.006 ms/op
Iteration   1: 3.344 ±(99.9%) 0.009 ms/op
Iteration   2: 3.467 ±(99.9%) 0.010 ms/op
Iteration   3: 3.360 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.390 ±(99.9%) 1.219 ms/op [Average]
  (min, avg, max) = (3.344, 3.390, 3.467), stdev = 0.067
  CI (99.9%): [2.171, 4.609] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.009 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.005 ms/op
Iteration   1: 3.332 ±(99.9%) 0.004 ms/op
Iteration   2: 3.158 ±(99.9%) 0.013 ms/op
Iteration   3: 3.300 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.263 ±(99.9%) 1.693 ms/op [Average]
  (min, avg, max) = (3.158, 3.263, 3.332), stdev = 0.093
  CI (99.9%): [1.571, 4.956] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.996 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.004 ms/op
Iteration   1: 3.375 ±(99.9%) 0.008 ms/op
Iteration   2: 3.416 ±(99.9%) 0.011 ms/op
Iteration   3: 3.416 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.403 ±(99.9%) 0.429 ms/op [Average]
  (min, avg, max) = (3.375, 3.403, 3.416), stdev = 0.024
  CI (99.9%): [2.974, 3.831] (assumes normal distribution)


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
# Warmup Iteration   1: 9.656 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.005 ms/op
Iteration   1: 3.931 ±(99.9%) 0.015 ms/op
Iteration   2: 4.178 ±(99.9%) 0.008 ms/op
Iteration   3: 3.897 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.002 ±(99.9%) 2.797 ms/op [Average]
  (min, avg, max) = (3.897, 4.002, 4.178), stdev = 0.153
  CI (99.9%): [1.205, 6.799] (assumes normal distribution)


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
# Warmup Iteration   1: 9.777 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.010 ms/op
Iteration   1: 3.422 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.262 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   4.035 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.411 ms/op
                 createUser·p0.999:  19.456 ms/op
                 createUser·p0.9999: 24.150 ms/op
                 createUser·p1.00:   25.330 ms/op

Iteration   2: 3.350 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  22.107 ms/op
                 createUser·p0.9999: 24.606 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   3: 3.284 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.245 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.638 ms/op
                 createUser·p0.999:  16.705 ms/op
                 createUser·p0.9999: 24.060 ms/op
                 createUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 286295
  mean =      3.351 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10230 
    [ 2.500,  5.000) = 271667 
    [ 5.000,  7.500) = 3457 
    [ 7.500, 10.000) = 475 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 144 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.245 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     17.030 ms/op
     p(99.9900) =     24.260 ms/op
     p(99.9990) =     25.166 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 8.242 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.008 ms/op
Iteration   1: 3.341 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  13.199 ms/op
                 existUser·p0.9999: 22.493 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 3.362 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  21.534 ms/op
                 existUser·p0.9999: 24.821 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   3: 3.391 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  18.678 ms/op
                 existUser·p0.9999: 26.481 ms/op
                 existUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285214
  mean =      3.364 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11201 
    [ 2.500,  5.000) = 267845 
    [ 5.000,  7.500) = 5090 
    [ 7.500, 10.000) = 529 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     17.491 ms/op
     p(99.9900) =     25.887 ms/op
     p(99.9990) =     26.903 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 8.152 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.011 ms/op
Iteration   1: 3.443 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  19.136 ms/op
                 getUser·p0.9999: 22.567 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   2: 3.491 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.745 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  21.767 ms/op
                 getUser·p0.9999: 29.060 ms/op
                 getUser·p1.00:   29.983 ms/op

Iteration   3: 3.538 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.487 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  19.023 ms/op
                 getUser·p0.9999: 27.851 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275199
  mean =      3.490 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11457 
    [ 2.500,  5.000) = 254508 
    [ 5.000,  7.500) = 7817 
    [ 7.500, 10.000) = 846 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.021 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     19.163 ms/op
     p(99.9900) =     28.246 ms/op
     p(99.9990) =     29.540 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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
# Warmup Iteration   1: 11.562 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.440 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.014 ms/op
Iteration   1: 3.996 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  19.560 ms/op
                 listUser·p0.9999: 25.428 ms/op
                 listUser·p1.00:   26.214 ms/op

Iteration   2: 3.923 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  16.329 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   3: 4.095 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.064 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  13.860 ms/op
                 listUser·p0.9999: 17.629 ms/op
                 listUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239464
  mean =      4.004 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 228579 
    [ 5.000,  7.500) = 8937 
    [ 7.500, 10.000) = 1053 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 286 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     16.335 ms/op
     p(99.9900) =     23.922 ms/op
     p(99.9990) =     26.005 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.227 ± 2.711  ops/ms
ClientPb.existUser                       thrpt       3   9.467 ± 4.020  ops/ms
ClientPb.getUser                         thrpt       3   9.403 ± 2.456  ops/ms
ClientPb.listUser                        thrpt       3   8.157 ± 0.517  ops/ms
ClientPb.createUser                       avgt       3   3.390 ± 1.219   ms/op
ClientPb.existUser                        avgt       3   3.263 ± 1.693   ms/op
ClientPb.getUser                          avgt       3   3.403 ± 0.429   ms/op
ClientPb.listUser                         avgt       3   4.002 ± 2.797   ms/op
ClientPb.createUser                     sample  286295   3.351 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.245           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.538           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.030           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.260           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.330           ms/op
ClientPb.existUser                      sample  285214   3.364 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.114           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.005           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.491           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.887           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.034           ms/op
ClientPb.getUser                        sample  275199   3.490 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.021           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.349           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.163           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.246           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.983           ms/op
ClientPb.listUser                       sample  239464   4.004 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.241           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.078           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.335           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.922           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.214           ms/op
