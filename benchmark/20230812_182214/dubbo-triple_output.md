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
# Warmup Iteration   1: 2.522 ops/ms
# Warmup Iteration   2: 6.307 ops/ms
# Warmup Iteration   3: 9.037 ops/ms
Iteration   1: 9.748 ops/ms
Iteration   2: 9.401 ops/ms
Iteration   3: 9.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.536 ±(99.9%) 3.386 ops/ms [Average]
  (min, avg, max) = (9.401, 9.536, 9.748), stdev = 0.186
  CI (99.9%): [6.150, 12.922] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.594 ops/ms
# Warmup Iteration   2: 9.318 ops/ms
# Warmup Iteration   3: 10.055 ops/ms
Iteration   1: 10.534 ops/ms
Iteration   2: 10.417 ops/ms
Iteration   3: 10.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.385 ±(99.9%) 3.047 ops/ms [Average]
  (min, avg, max) = (10.204, 10.385, 10.534), stdev = 0.167
  CI (99.9%): [7.338, 13.432] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.351 ops/ms
# Warmup Iteration   2: 9.024 ops/ms
# Warmup Iteration   3: 9.815 ops/ms
Iteration   1: 9.481 ops/ms
Iteration   2: 10.018 ops/ms
Iteration   3: 10.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.884 ±(99.9%) 6.502 ops/ms [Average]
  (min, avg, max) = (9.481, 9.884, 10.155), stdev = 0.356
  CI (99.9%): [3.382, 16.386] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.303 ops/ms
# Warmup Iteration   2: 7.665 ops/ms
# Warmup Iteration   3: 8.284 ops/ms
Iteration   1: 8.531 ops/ms
Iteration   2: 8.255 ops/ms
Iteration   3: 8.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.396 ±(99.9%) 2.519 ops/ms [Average]
  (min, avg, max) = (8.255, 8.396, 8.531), stdev = 0.138
  CI (99.9%): [5.877, 10.915] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.334 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.004 ms/op
Iteration   1: 3.286 ±(99.9%) 0.006 ms/op
Iteration   2: 3.204 ±(99.9%) 0.007 ms/op
Iteration   3: 3.197 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.229 ±(99.9%) 0.908 ms/op [Average]
  (min, avg, max) = (3.197, 3.229, 3.286), stdev = 0.050
  CI (99.9%): [2.321, 4.137] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.249 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.400 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.005 ms/op
Iteration   1: 3.100 ±(99.9%) 0.004 ms/op
Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
Iteration   3: 3.275 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.193 ±(99.9%) 1.610 ms/op [Average]
  (min, avg, max) = (3.100, 3.193, 3.275), stdev = 0.088
  CI (99.9%): [1.583, 4.803] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.784 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.004 ms/op
Iteration   1: 3.145 ±(99.9%) 0.005 ms/op
Iteration   2: 3.103 ±(99.9%) 0.005 ms/op
Iteration   3: 3.148 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.132 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (3.103, 3.132, 3.148), stdev = 0.025
  CI (99.9%): [2.678, 3.586] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.039 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.290 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.004 ms/op
Iteration   1: 3.823 ±(99.9%) 0.007 ms/op
Iteration   2: 3.766 ±(99.9%) 0.007 ms/op
Iteration   3: 3.771 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.787 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (3.766, 3.787, 3.823), stdev = 0.031
  CI (99.9%): [3.216, 4.358] (assumes normal distribution)


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
# Warmup Iteration   1: 8.064 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.008 ms/op
Iteration   1: 3.181 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  9.197 ms/op
                 createUser·p0.9999: 18.446 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   2: 3.321 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.599 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  17.773 ms/op
                 createUser·p0.9999: 27.243 ms/op
                 createUser·p1.00:   29.098 ms/op

Iteration   3: 3.292 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.507 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  15.962 ms/op
                 createUser·p0.9999: 24.101 ms/op
                 createUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293853
  mean =      3.263 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18499 
    [ 2.500,  5.000) = 269270 
    [ 5.000,  7.500) = 4845 
    [ 7.500, 10.000) = 817 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.705 ms/op
     p(99.9000) =     15.921 ms/op
     p(99.9900) =     25.468 ms/op
     p(99.9990) =     27.371 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.805 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.008 ms/op
Iteration   1: 3.292 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.319 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.162 ms/op
                 existUser·p0.999:  9.203 ms/op
                 existUser·p0.9999: 20.663 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   2: 3.214 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.454 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.875 ms/op
                 existUser·p0.999:  11.338 ms/op
                 existUser·p0.9999: 22.122 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   3: 3.232 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  12.797 ms/op
                 existUser·p0.9999: 24.252 ms/op
                 existUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295453
  mean =      3.246 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22880 
    [ 2.500,  5.000) = 263353 
    [ 5.000,  7.500) = 7773 
    [ 7.500, 10.000) = 996 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     11.944 ms/op
     p(99.9900) =     23.441 ms/op
     p(99.9990) =     24.880 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 8.064 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.011 ms/op
Iteration   1: 3.398 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.473 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  17.800 ms/op
                 getUser·p0.9999: 20.734 ms/op
                 getUser·p1.00:   21.692 ms/op

Iteration   2: 3.122 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.440 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.346 ms/op
                 getUser·p0.95:   3.539 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  11.343 ms/op
                 getUser·p0.9999: 22.086 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   3: 3.306 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.677 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  15.849 ms/op
                 getUser·p0.9999: 21.441 ms/op
                 getUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293200
  mean =      3.271 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13506 
    [ 2.500,  5.000) = 270414 
    [ 5.000,  7.500) = 7455 
    [ 7.500, 10.000) = 1295 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 158 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.440 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     15.742 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     22.817 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 7.899 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.012 ms/op
Iteration   1: 3.857 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.075 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  15.140 ms/op
                 listUser·p0.9999: 22.774 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   2: 3.803 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.855 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.573 ms/op
                 listUser·p0.999:  14.695 ms/op
                 listUser·p0.9999: 21.201 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   3: 3.752 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   7.546 ms/op
                 listUser·p0.999:  12.826 ms/op
                 listUser·p0.9999: 15.991 ms/op
                 listUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252152
  mean =      3.803 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 242190 
    [ 5.000,  7.500) = 7082 
    [ 7.500, 10.000) = 1959 
    [10.000, 12.500) = 452 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.855 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.725 ms/op
     p(99.9000) =     14.383 ms/op
     p(99.9900) =     21.201 ms/op
     p(99.9990) =     23.559 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.536 ± 3.386  ops/ms
ClientPb.existUser                       thrpt       3  10.385 ± 3.047  ops/ms
ClientPb.getUser                         thrpt       3   9.884 ± 6.502  ops/ms
ClientPb.listUser                        thrpt       3   8.396 ± 2.519  ops/ms
ClientPb.createUser                       avgt       3   3.229 ± 0.908   ms/op
ClientPb.existUser                        avgt       3   3.193 ± 1.610   ms/op
ClientPb.getUser                          avgt       3   3.132 ± 0.454   ms/op
ClientPb.listUser                         avgt       3   3.787 ± 0.571   ms/op
ClientPb.createUser                     sample  293853   3.263 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.507           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.645           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.705           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.921           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.468           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.098           ms/op
ClientPb.existUser                      sample  295453   3.246 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.135           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.160           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.944           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.441           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.821           ms/op
ClientPb.getUser                        sample  293200   3.271 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.440           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.650           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.141           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.726           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.742           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.725           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.478           ms/op
ClientPb.listUser                       sample  252152   3.803 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.855           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.092           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.725           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.383           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.201           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.674           ms/op
