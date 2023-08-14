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
# Warmup Iteration   1: 2.412 ops/ms
# Warmup Iteration   2: 6.135 ops/ms
# Warmup Iteration   3: 9.293 ops/ms
Iteration   1: 9.750 ops/ms
Iteration   2: 9.475 ops/ms
Iteration   3: 9.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.552 ±(99.9%) 3.159 ops/ms [Average]
  (min, avg, max) = (9.430, 9.552, 9.750), stdev = 0.173
  CI (99.9%): [6.393, 12.710] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.744 ops/ms
# Warmup Iteration   2: 9.140 ops/ms
# Warmup Iteration   3: 9.580 ops/ms
Iteration   1: 9.833 ops/ms
Iteration   2: 9.843 ops/ms
Iteration   3: 10.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.999 ±(99.9%) 5.088 ops/ms [Average]
  (min, avg, max) = (9.833, 9.999, 10.321), stdev = 0.279
  CI (99.9%): [4.911, 15.087] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.204 ops/ms
# Warmup Iteration   2: 8.618 ops/ms
# Warmup Iteration   3: 9.384 ops/ms
Iteration   1: 9.508 ops/ms
Iteration   2: 9.633 ops/ms
Iteration   3: 9.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.620 ±(99.9%) 1.931 ops/ms [Average]
  (min, avg, max) = (9.508, 9.620, 9.718), stdev = 0.106
  CI (99.9%): [7.689, 11.550] (assumes normal distribution)


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
# Warmup Iteration   1: 3.137 ops/ms
# Warmup Iteration   2: 7.507 ops/ms
# Warmup Iteration   3: 8.606 ops/ms
Iteration   1: 8.623 ops/ms
Iteration   2: 8.307 ops/ms
Iteration   3: 8.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.488 ±(99.9%) 2.978 ops/ms [Average]
  (min, avg, max) = (8.307, 8.488, 8.623), stdev = 0.163
  CI (99.9%): [5.510, 11.466] (assumes normal distribution)


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
# Warmup Iteration   1: 9.538 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.822 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.005 ms/op
Iteration   1: 3.309 ±(99.9%) 0.002 ms/op
Iteration   2: 3.222 ±(99.9%) 0.007 ms/op
Iteration   3: 3.299 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.277 ±(99.9%) 0.871 ms/op [Average]
  (min, avg, max) = (3.222, 3.277, 3.309), stdev = 0.048
  CI (99.9%): [2.406, 4.147] (assumes normal distribution)


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
# Warmup Iteration   1: 6.734 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.422 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.003 ms/op
Iteration   1: 3.233 ±(99.9%) 0.003 ms/op
Iteration   2: 3.105 ±(99.9%) 0.004 ms/op
Iteration   3: 3.109 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.149 ±(99.9%) 1.326 ms/op [Average]
  (min, avg, max) = (3.105, 3.149, 3.233), stdev = 0.073
  CI (99.9%): [1.823, 4.475] (assumes normal distribution)


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
# Warmup Iteration   1: 9.461 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.005 ms/op
Iteration   1: 3.212 ±(99.9%) 0.003 ms/op
Iteration   2: 3.211 ±(99.9%) 0.004 ms/op
Iteration   3: 3.112 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.178 ±(99.9%) 1.053 ms/op [Average]
  (min, avg, max) = (3.112, 3.178, 3.212), stdev = 0.058
  CI (99.9%): [2.125, 4.232] (assumes normal distribution)


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
# Warmup Iteration   1: 9.164 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.005 ms/op
Iteration   1: 3.830 ±(99.9%) 0.003 ms/op
Iteration   2: 3.847 ±(99.9%) 0.007 ms/op
Iteration   3: 3.810 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.829 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (3.810, 3.829, 3.847), stdev = 0.019
  CI (99.9%): [3.491, 4.168] (assumes normal distribution)


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
# Warmup Iteration   1: 7.984 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.010 ms/op
Iteration   1: 3.335 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.039 ms/op
                 createUser·p0.999:  17.172 ms/op
                 createUser·p0.9999: 24.471 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   2: 3.276 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  14.342 ms/op
                 createUser·p0.9999: 22.454 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   3: 3.150 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  15.787 ms/op
                 createUser·p0.9999: 31.911 ms/op
                 createUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295041
  mean =      3.252 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22277 
    [ 2.500,  5.000) = 266523 
    [ 5.000,  7.500) = 4929 
    [ 7.500, 10.000) = 878 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     15.693 ms/op
     p(99.9900) =     30.376 ms/op
     p(99.9990) =     32.639 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


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
# Warmup Iteration   1: 7.338 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.476 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.009 ms/op
Iteration   1: 3.120 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  12.090 ms/op
                 existUser·p0.9999: 24.469 ms/op
                 existUser·p1.00:   26.247 ms/op

Iteration   2: 3.129 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  13.173 ms/op
                 existUser·p0.9999: 22.177 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   3: 3.103 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.270 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  11.305 ms/op
                 existUser·p0.9999: 21.574 ms/op
                 existUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307865
  mean =      3.118 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9663 
    [ 2.500,  5.000) = 292093 
    [ 5.000,  7.500) = 5010 
    [ 7.500, 10.000) = 691 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 159 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.270 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     22.888 ms/op
     p(99.9990) =     25.327 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


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
# Warmup Iteration   1: 9.109 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.010 ms/op
Iteration   1: 3.398 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.906 ms/op
                 getUser·p0.999:  18.016 ms/op
                 getUser·p0.9999: 21.272 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   2: 3.242 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.372 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   6.452 ms/op
                 getUser·p0.999:  9.781 ms/op
                 getUser·p0.9999: 23.110 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   3: 3.288 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.341 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  12.190 ms/op
                 getUser·p0.9999: 20.611 ms/op
                 getUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289915
  mean =      3.308 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15518 
    [ 2.500,  5.000) = 264336 
    [ 5.000,  7.500) = 8300 
    [ 7.500, 10.000) = 1244 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.724 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.075 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.232 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.013 ms/op
Iteration   1: 3.950 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.536 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  18.678 ms/op
                 listUser·p0.9999: 21.489 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   2: 3.799 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.763 ms/op
                 listUser·p0.999:  13.795 ms/op
                 listUser·p0.9999: 15.246 ms/op
                 listUser·p1.00:   16.499 ms/op

Iteration   3: 3.887 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  12.829 ms/op
                 listUser·p0.9999: 16.646 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247630
  mean =      3.878 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 235427 
    [ 5.000,  7.500) = 8709 
    [ 7.500, 10.000) = 2545 
    [10.000, 12.500) = 399 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      8.053 ms/op
     p(99.9000) =     14.113 ms/op
     p(99.9900) =     20.455 ms/op
     p(99.9990) =     22.104 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.552 ± 3.159  ops/ms
ClientPb.existUser                       thrpt       3   9.999 ± 5.088  ops/ms
ClientPb.getUser                         thrpt       3   9.620 ± 1.931  ops/ms
ClientPb.listUser                        thrpt       3   8.488 ± 2.978  ops/ms
ClientPb.createUser                       avgt       3   3.277 ± 0.871   ms/op
ClientPb.existUser                        avgt       3   3.149 ± 1.326   ms/op
ClientPb.getUser                          avgt       3   3.178 ± 1.053   ms/op
ClientPb.listUser                         avgt       3   3.829 ± 0.339   ms/op
ClientPb.createUser                     sample  295041   3.252 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.922           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.592           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.693           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.376           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.702           ms/op
ClientPb.existUser                      sample  307865   3.118 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.270           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.156           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.888           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.247           ms/op
ClientPb.getUser                        sample  289915   3.308 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.190           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.678           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.724           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.270           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.479           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.724           ms/op
ClientPb.listUser                       sample  247630   3.878 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.536           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.703           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.186           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.113           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.455           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.348           ms/op
