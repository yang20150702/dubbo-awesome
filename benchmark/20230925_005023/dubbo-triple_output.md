# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.612 ops/ms
# Warmup Iteration   2: 6.471 ops/ms
# Warmup Iteration   3: 8.904 ops/ms
Iteration   1: 9.668 ops/ms
Iteration   2: 9.646 ops/ms
Iteration   3: 9.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.657 ±(99.9%) 0.209 ops/ms [Average]
  (min, avg, max) = (9.646, 9.657, 9.668), stdev = 0.011
  CI (99.9%): [9.447, 9.866] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.034 ops/ms
# Warmup Iteration   2: 9.079 ops/ms
# Warmup Iteration   3: 9.928 ops/ms
Iteration   1: 9.994 ops/ms
Iteration   2: 10.064 ops/ms
Iteration   3: 10.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.077 ±(99.9%) 1.656 ops/ms [Average]
  (min, avg, max) = (9.994, 10.077, 10.174), stdev = 0.091
  CI (99.9%): [8.421, 11.733] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.724 ops/ms
# Warmup Iteration   2: 9.000 ops/ms
# Warmup Iteration   3: 9.407 ops/ms
Iteration   1: 9.688 ops/ms
Iteration   2: 9.655 ops/ms
Iteration   3: 9.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.611 ±(99.9%) 1.922 ops/ms [Average]
  (min, avg, max) = (9.491, 9.611, 9.688), stdev = 0.105
  CI (99.9%): [7.689, 11.533] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.986 ops/ms
# Warmup Iteration   2: 7.574 ops/ms
# Warmup Iteration   3: 8.329 ops/ms
Iteration   1: 8.140 ops/ms
Iteration   2: 8.275 ops/ms
Iteration   3: 8.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.265 ±(99.9%) 2.198 ops/ms [Average]
  (min, avg, max) = (8.140, 8.265, 8.380), stdev = 0.120
  CI (99.9%): [6.067, 10.463] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.200 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.514 ±(99.9%) 0.003 ms/op
Iteration   1: 3.311 ±(99.9%) 0.005 ms/op
Iteration   2: 3.300 ±(99.9%) 0.005 ms/op
Iteration   3: 3.302 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.304 ±(99.9%) 0.102 ms/op [Average]
  (min, avg, max) = (3.300, 3.304, 3.311), stdev = 0.006
  CI (99.9%): [3.202, 3.406] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.433 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.289 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.003 ms/op
Iteration   1: 3.125 ±(99.9%) 0.004 ms/op
Iteration   2: 3.187 ±(99.9%) 0.002 ms/op
Iteration   3: 3.227 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.180 ±(99.9%) 0.938 ms/op [Average]
  (min, avg, max) = (3.125, 3.180, 3.227), stdev = 0.051
  CI (99.9%): [2.242, 4.118] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.476 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.005 ms/op
Iteration   1: 3.207 ±(99.9%) 0.006 ms/op
Iteration   2: 3.219 ±(99.9%) 0.004 ms/op
Iteration   3: 3.269 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.231 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (3.207, 3.231, 3.269), stdev = 0.033
  CI (99.9%): [2.632, 3.831] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.325 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.269 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.005 ms/op
Iteration   1: 3.889 ±(99.9%) 0.004 ms/op
Iteration   2: 3.958 ±(99.9%) 0.006 ms/op
Iteration   3: 3.914 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.921 ±(99.9%) 0.637 ms/op [Average]
  (min, avg, max) = (3.889, 3.921, 3.958), stdev = 0.035
  CI (99.9%): [3.284, 4.557] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.133 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.415 ±(99.9%) 0.010 ms/op
Iteration   1: 3.329 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  17.170 ms/op
                 createUser·p0.9999: 19.875 ms/op
                 createUser·p1.00:   20.644 ms/op

Iteration   2: 3.269 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  21.629 ms/op
                 createUser·p0.9999: 25.795 ms/op
                 createUser·p1.00:   28.541 ms/op

Iteration   3: 3.366 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  17.071 ms/op
                 createUser·p0.9999: 20.480 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289097
  mean =      3.321 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10576 
    [ 2.500,  5.000) = 270340 
    [ 5.000,  7.500) = 6800 
    [ 7.500, 10.000) = 662 
    [10.000, 12.500) = 245 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 160 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     25.398 ms/op
     p(99.9990) =     26.643 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.037 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.424 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.008 ms/op
Iteration   1: 3.225 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  13.685 ms/op
                 existUser·p0.9999: 22.252 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   2: 3.293 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.409 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   6.414 ms/op
                 existUser·p0.999:  16.592 ms/op
                 existUser·p0.9999: 22.624 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   3: 3.251 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   4.050 ms/op
                 existUser·p0.99:   6.595 ms/op
                 existUser·p0.999:  9.120 ms/op
                 existUser·p0.9999: 21.779 ms/op
                 existUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294755
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16451 
    [ 2.500,  5.000) = 269042 
    [ 5.000,  7.500) = 8315 
    [ 7.500, 10.000) = 445 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     13.299 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     23.498 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.334 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.490 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.012 ms/op
Iteration   1: 3.288 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  15.761 ms/op
                 getUser·p0.9999: 17.179 ms/op
                 getUser·p1.00:   17.990 ms/op

Iteration   2: 3.310 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  15.853 ms/op
                 getUser·p0.9999: 19.946 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   3: 3.289 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.563 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  15.469 ms/op
                 getUser·p0.9999: 25.404 ms/op
                 getUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291066
  mean =      3.296 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5520 
    [ 2.500,  5.000) = 277605 
    [ 5.000,  7.500) = 6760 
    [ 7.500, 10.000) = 492 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 258 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      6.319 ms/op
     p(99.9000) =     15.729 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     26.056 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.723 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.013 ms/op
Iteration   1: 3.912 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  18.616 ms/op
                 listUser·p0.9999: 21.249 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   2: 3.904 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  13.959 ms/op
                 listUser·p0.9999: 15.663 ms/op
                 listUser·p1.00:   15.909 ms/op

Iteration   3: 3.886 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.389 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.574 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  14.107 ms/op
                 listUser·p0.9999: 22.176 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245990
  mean =      3.901 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 140 
    [ 2.500,  5.000) = 236339 
    [ 5.000,  7.500) = 7158 
    [ 7.500, 10.000) = 1414 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 448 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     20.998 ms/op
     p(99.9990) =     23.185 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.657 ± 0.209  ops/ms
ClientPb.existUser                       thrpt       3  10.077 ± 1.656  ops/ms
ClientPb.getUser                         thrpt       3   9.611 ± 1.922  ops/ms
ClientPb.listUser                        thrpt       3   8.265 ± 2.198  ops/ms
ClientPb.createUser                       avgt       3   3.304 ± 0.102   ms/op
ClientPb.existUser                        avgt       3   3.180 ± 0.938   ms/op
ClientPb.getUser                          avgt       3   3.231 ± 0.599   ms/op
ClientPb.listUser                         avgt       3   3.921 ± 0.637   ms/op
ClientPb.createUser                     sample  289097   3.321 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.952           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.067           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.423           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.990           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.398           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.541           ms/op
ClientPb.existUser                      sample  294755   3.256 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.931           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.299           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.282           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.986           ms/op
ClientPb.getUser                        sample  291066   3.296 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.108           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.625           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.319           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.729           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.855           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.280           ms/op
ClientPb.listUser                       sample  245990   3.901 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.389           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.723           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.336           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.998           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.495           ms/op
