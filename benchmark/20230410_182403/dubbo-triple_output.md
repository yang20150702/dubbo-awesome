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
# Warmup Iteration   1: 2.680 ops/ms
# Warmup Iteration   2: 6.502 ops/ms
# Warmup Iteration   3: 9.469 ops/ms
Iteration   1: 9.614 ops/ms
Iteration   2: 10.048 ops/ms
Iteration   3: 9.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.721 ±(99.9%) 5.260 ops/ms [Average]
  (min, avg, max) = (9.501, 9.721, 10.048), stdev = 0.288
  CI (99.9%): [4.461, 14.981] (assumes normal distribution)


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
# Warmup Iteration   1: 3.766 ops/ms
# Warmup Iteration   2: 9.312 ops/ms
# Warmup Iteration   3: 10.003 ops/ms
Iteration   1: 10.451 ops/ms
Iteration   2: 10.111 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.364 ±(99.9%) 4.067 ops/ms [Average]
  (min, avg, max) = (10.111, 10.364, 10.530), stdev = 0.223
  CI (99.9%): [6.297, 14.431] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.573 ops/ms
# Warmup Iteration   2: 8.983 ops/ms
# Warmup Iteration   3: 9.506 ops/ms
Iteration   1: 10.343 ops/ms
Iteration   2: 9.976 ops/ms
Iteration   3: 10.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.284 ±(99.9%) 5.159 ops/ms [Average]
  (min, avg, max) = (9.976, 10.284, 10.533), stdev = 0.283
  CI (99.9%): [5.125, 15.443] (assumes normal distribution)


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
# Warmup Iteration   1: 3.376 ops/ms
# Warmup Iteration   2: 7.893 ops/ms
# Warmup Iteration   3: 8.463 ops/ms
Iteration   1: 8.519 ops/ms
Iteration   2: 8.515 ops/ms
Iteration   3: 8.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.561 ±(99.9%) 1.399 ops/ms [Average]
  (min, avg, max) = (8.515, 8.561, 8.650), stdev = 0.077
  CI (99.9%): [7.163, 9.960] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.834 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.002 ms/op
Iteration   1: 3.261 ±(99.9%) 0.005 ms/op
Iteration   2: 3.239 ±(99.9%) 0.003 ms/op
Iteration   3: 3.114 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.205 ±(99.9%) 1.450 ms/op [Average]
  (min, avg, max) = (3.114, 3.205, 3.261), stdev = 0.079
  CI (99.9%): [1.755, 4.655] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.001 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.003 ms/op
Iteration   1: 3.043 ±(99.9%) 0.005 ms/op
Iteration   2: 2.976 ±(99.9%) 0.006 ms/op
Iteration   3: 3.038 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.019 ±(99.9%) 0.673 ms/op [Average]
  (min, avg, max) = (2.976, 3.019, 3.043), stdev = 0.037
  CI (99.9%): [2.346, 3.692] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.077 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.002 ms/op
Iteration   1: 3.255 ±(99.9%) 0.006 ms/op
Iteration   2: 3.122 ±(99.9%) 0.004 ms/op
Iteration   3: 3.112 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.163 ±(99.9%) 1.461 ms/op [Average]
  (min, avg, max) = (3.112, 3.163, 3.255), stdev = 0.080
  CI (99.9%): [1.702, 4.624] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.656 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.073 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.775 ±(99.9%) 0.008 ms/op
Iteration   1: 3.766 ±(99.9%) 0.008 ms/op
Iteration   2: 3.704 ±(99.9%) 0.009 ms/op
Iteration   3: 3.663 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.711 ±(99.9%) 0.951 ms/op [Average]
  (min, avg, max) = (3.663, 3.711, 3.766), stdev = 0.052
  CI (99.9%): [2.760, 4.662] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.271 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.009 ms/op
Iteration   1: 3.220 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.511 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  11.241 ms/op
                 createUser·p0.9999: 23.857 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   2: 3.143 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.871 ms/op
                 createUser·p0.999:  19.666 ms/op
                 createUser·p0.9999: 23.384 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   3: 3.129 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.544 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.285 ms/op
                 createUser·p0.95:   3.465 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  17.302 ms/op
                 createUser·p0.9999: 26.757 ms/op
                 createUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303400
  mean =      3.163 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20748 
    [ 2.500,  5.000) = 276956 
    [ 5.000,  7.500) = 4637 
    [ 7.500, 10.000) = 614 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     18.239 ms/op
     p(99.9900) =     23.811 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.415 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.008 ms/op
Iteration   1: 3.076 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.307 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  10.568 ms/op
                 existUser·p0.9999: 24.989 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   2: 3.121 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  13.441 ms/op
                 existUser·p0.9999: 24.413 ms/op
                 existUser·p1.00:   25.657 ms/op

Iteration   3: 3.085 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.307 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  9.748 ms/op
                 existUser·p0.9999: 20.206 ms/op
                 existUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310202
  mean =      3.093 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15429 
    [ 2.500,  5.000) = 287623 
    [ 5.000,  7.500) = 6252 
    [ 7.500, 10.000) = 529 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.624 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     12.888 ms/op
     p(99.9900) =     24.609 ms/op
     p(99.9990) =     25.425 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 7.587 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.011 ms/op
Iteration   1: 3.111 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.514 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  9.060 ms/op
                 getUser·p0.9999: 20.316 ms/op
                 getUser·p1.00:   20.677 ms/op

Iteration   2: 3.229 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.094 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  13.540 ms/op
                 getUser·p0.9999: 34.960 ms/op
                 getUser·p1.00:   35.652 ms/op

Iteration   3: 3.303 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.511 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  16.754 ms/op
                 getUser·p0.9999: 22.064 ms/op
                 getUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298611
  mean =      3.212 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16033 
    [ 2.500,  5.000) = 276313 
    [ 5.000,  7.500) = 5476 
    [ 7.500, 10.000) = 378 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     34.275 ms/op
     p(99.9990) =     35.652 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 8.890 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 4.191 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.011 ms/op
Iteration   1: 3.763 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  14.270 ms/op
                 listUser·p0.9999: 20.791 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   2: 3.821 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.726 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  13.926 ms/op
                 listUser·p0.9999: 20.063 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   3: 3.790 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  15.445 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252899
  mean =      3.791 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 95 
    [ 2.500,  5.000) = 244530 
    [ 5.000,  7.500) = 6057 
    [ 7.500, 10.000) = 1420 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 333 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.726 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     14.829 ms/op
     p(99.9900) =     20.068 ms/op
     p(99.9990) =     21.446 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.721 ± 5.260  ops/ms
ClientPb.existUser                       thrpt       3  10.364 ± 4.067  ops/ms
ClientPb.getUser                         thrpt       3  10.284 ± 5.159  ops/ms
ClientPb.listUser                        thrpt       3   8.561 ± 1.399  ops/ms
ClientPb.createUser                       avgt       3   3.205 ± 1.450   ms/op
ClientPb.existUser                        avgt       3   3.019 ± 0.673   ms/op
ClientPb.getUser                          avgt       3   3.163 ± 1.461   ms/op
ClientPb.listUser                         avgt       3   3.711 ± 0.951   ms/op
ClientPb.createUser                     sample  303400   3.163 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.100           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.469           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.239           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.811           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.132           ms/op
ClientPb.existUser                      sample  310202   3.093 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.307           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.624           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.800           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.888           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.609           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.657           ms/op
ClientPb.getUser                        sample  298611   3.212 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.094           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.617           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.533           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.275           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.652           ms/op
ClientPb.listUser                       sample  252899   3.791 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.726           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.084           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.184           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.829           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.068           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.889           ms/op
