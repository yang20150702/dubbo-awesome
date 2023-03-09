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
# Warmup Iteration   1: 2.330 ops/ms
# Warmup Iteration   2: 5.465 ops/ms
# Warmup Iteration   3: 8.609 ops/ms
Iteration   1: 9.125 ops/ms
Iteration   2: 9.512 ops/ms
Iteration   3: 9.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.348 ±(99.9%) 3.655 ops/ms [Average]
  (min, avg, max) = (9.125, 9.348, 9.512), stdev = 0.200
  CI (99.9%): [5.693, 13.004] (assumes normal distribution)


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
# Warmup Iteration   1: 3.191 ops/ms
# Warmup Iteration   2: 9.209 ops/ms
# Warmup Iteration   3: 9.483 ops/ms
Iteration   1: 9.878 ops/ms
Iteration   2: 9.423 ops/ms
Iteration   3: 9.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.527 ±(99.9%) 5.697 ops/ms [Average]
  (min, avg, max) = (9.280, 9.527, 9.878), stdev = 0.312
  CI (99.9%): [3.830, 15.224] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.971 ops/ms
# Warmup Iteration   2: 8.374 ops/ms
# Warmup Iteration   3: 9.201 ops/ms
Iteration   1: 9.639 ops/ms
Iteration   2: 9.512 ops/ms
Iteration   3: 9.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.456 ±(99.9%) 3.956 ops/ms [Average]
  (min, avg, max) = (9.217, 9.456, 9.639), stdev = 0.217
  CI (99.9%): [5.500, 13.412] (assumes normal distribution)


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
# Warmup Iteration   1: 2.670 ops/ms
# Warmup Iteration   2: 7.207 ops/ms
# Warmup Iteration   3: 8.159 ops/ms
Iteration   1: 7.996 ops/ms
Iteration   2: 8.025 ops/ms
Iteration   3: 8.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.078 ±(99.9%) 2.150 ops/ms [Average]
  (min, avg, max) = (7.996, 8.078, 8.213), stdev = 0.118
  CI (99.9%): [5.928, 10.228] (assumes normal distribution)


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
# Warmup Iteration   1: 8.901 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.008 ms/op
Iteration   1: 3.344 ±(99.9%) 0.004 ms/op
Iteration   2: 3.497 ±(99.9%) 0.005 ms/op
Iteration   3: 3.325 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.389 ±(99.9%) 1.723 ms/op [Average]
  (min, avg, max) = (3.325, 3.389, 3.497), stdev = 0.094
  CI (99.9%): [1.665, 5.112] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.598 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.005 ms/op
Iteration   1: 3.291 ±(99.9%) 0.006 ms/op
Iteration   2: 3.174 ±(99.9%) 0.011 ms/op
Iteration   3: 3.173 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.213 ±(99.9%) 1.239 ms/op [Average]
  (min, avg, max) = (3.173, 3.213, 3.291), stdev = 0.068
  CI (99.9%): [1.974, 4.452] (assumes normal distribution)


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
# Warmup Iteration   1: 8.618 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.687 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.004 ms/op
Iteration   1: 3.461 ±(99.9%) 0.003 ms/op
Iteration   2: 3.500 ±(99.9%) 0.007 ms/op
Iteration   3: 3.379 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.447 ±(99.9%) 1.123 ms/op [Average]
  (min, avg, max) = (3.379, 3.447, 3.500), stdev = 0.062
  CI (99.9%): [2.323, 4.570] (assumes normal distribution)


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
# Warmup Iteration   1: 10.636 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.130 ±(99.9%) 0.009 ms/op
Iteration   1: 3.873 ±(99.9%) 0.010 ms/op
Iteration   2: 3.946 ±(99.9%) 0.013 ms/op
Iteration   3: 4.030 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.949 ±(99.9%) 1.429 ms/op [Average]
  (min, avg, max) = (3.873, 3.949, 4.030), stdev = 0.078
  CI (99.9%): [2.521, 5.378] (assumes normal distribution)


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
# Warmup Iteration   1: 10.221 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.008 ms/op
Iteration   1: 3.703 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   6.111 ms/op
                 createUser·p0.99:   7.561 ms/op
                 createUser·p0.999:  19.586 ms/op
                 createUser·p0.9999: 21.868 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   2: 3.469 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  23.888 ms/op
                 createUser·p0.9999: 28.829 ms/op
                 createUser·p1.00:   30.769 ms/op

Iteration   3: 3.384 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  20.017 ms/op
                 createUser·p0.9999: 29.901 ms/op
                 createUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273415
  mean =      3.514 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11665 
    [ 2.500,  5.000) = 251021 
    [ 5.000,  7.500) = 9154 
    [ 7.500, 10.000) = 981 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     19.713 ms/op
     p(99.9900) =     29.163 ms/op
     p(99.9990) =     30.769 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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
# Warmup Iteration   1: 9.227 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.613 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.374 ±(99.9%) 0.009 ms/op
Iteration   1: 3.370 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.378 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.886 ms/op
                 existUser·p0.999:  18.880 ms/op
                 existUser·p0.9999: 22.364 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   2: 3.219 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.503 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   5.425 ms/op
                 existUser·p0.999:  11.354 ms/op
                 existUser·p0.9999: 24.183 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   3: 3.325 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.182 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  8.634 ms/op
                 existUser·p0.9999: 26.356 ms/op
                 existUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290489
  mean =      3.303 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15218 
    [ 2.500,  5.000) = 269771 
    [ 5.000,  7.500) = 4584 
    [ 7.500, 10.000) = 476 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     11.330 ms/op
     p(99.9900) =     25.225 ms/op
     p(99.9990) =     28.085 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


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
# Warmup Iteration   1: 9.464 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.878 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.011 ms/op
Iteration   1: 3.463 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.944 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.752 ms/op
                 getUser·p0.999:  21.054 ms/op
                 getUser·p0.9999: 33.702 ms/op
                 getUser·p1.00:   33.751 ms/op

Iteration   2: 3.380 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.806 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  21.145 ms/op
                 getUser·p0.9999: 25.020 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   3: 3.451 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.380 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  23.291 ms/op
                 getUser·p0.9999: 28.752 ms/op
                 getUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279628
  mean =      3.431 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7843 
    [ 2.500,  5.000) = 262878 
    [ 5.000,  7.500) = 7797 
    [ 7.500, 10.000) = 696 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     30.607 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 9.849 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.673 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.013 ms/op
Iteration   1: 3.881 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.726 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  19.910 ms/op
                 listUser·p0.9999: 23.421 ms/op
                 listUser·p1.00:   24.183 ms/op

Iteration   2: 4.089 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.878 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  15.489 ms/op
                 listUser·p0.9999: 16.715 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   3: 3.884 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.523 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  14.806 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242952
  mean =      3.949 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 236440 
    [ 5.000,  7.500) = 4471 
    [ 7.500, 10.000) = 1281 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.726 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     21.814 ms/op
     p(99.9990) =     23.677 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.348 ± 3.655  ops/ms
ClientPb.existUser                       thrpt       3   9.527 ± 5.697  ops/ms
ClientPb.getUser                         thrpt       3   9.456 ± 3.956  ops/ms
ClientPb.listUser                        thrpt       3   8.078 ± 2.150  ops/ms
ClientPb.createUser                       avgt       3   3.389 ± 1.723   ms/op
ClientPb.existUser                        avgt       3   3.213 ± 1.239   ms/op
ClientPb.getUser                          avgt       3   3.447 ± 1.123   ms/op
ClientPb.listUser                         avgt       3   3.949 ± 1.429   ms/op
ClientPb.createUser                     sample  273415   3.514 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.143           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.514           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.184           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.713           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.163           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.933           ms/op
ClientPb.existUser                      sample  290489   3.303 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.182           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.010           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.530           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.330           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.225           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.211           ms/op
ClientPb.getUser                        sample  279628   3.431 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.380           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.266           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.607           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.751           ms/op
ClientPb.listUser                       sample  242952   3.949 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.726           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.809           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.516           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.814           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.183           ms/op
