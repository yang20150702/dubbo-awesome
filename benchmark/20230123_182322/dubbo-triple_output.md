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
# Warmup Iteration   1: 2.220 ops/ms
# Warmup Iteration   2: 5.859 ops/ms
# Warmup Iteration   3: 8.393 ops/ms
Iteration   1: 9.053 ops/ms
Iteration   2: 9.511 ops/ms
Iteration   3: 9.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.288 ±(99.9%) 4.183 ops/ms [Average]
  (min, avg, max) = (9.053, 9.288, 9.511), stdev = 0.229
  CI (99.9%): [5.105, 13.471] (assumes normal distribution)


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
# Warmup Iteration   1: 3.641 ops/ms
# Warmup Iteration   2: 8.962 ops/ms
# Warmup Iteration   3: 9.731 ops/ms
Iteration   1: 9.677 ops/ms
Iteration   2: 10.200 ops/ms
Iteration   3: 10.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.981 ±(99.9%) 4.952 ops/ms [Average]
  (min, avg, max) = (9.677, 9.981, 10.200), stdev = 0.271
  CI (99.9%): [5.029, 14.933] (assumes normal distribution)


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
# Warmup Iteration   1: 3.158 ops/ms
# Warmup Iteration   2: 8.403 ops/ms
# Warmup Iteration   3: 9.026 ops/ms
Iteration   1: 9.170 ops/ms
Iteration   2: 9.298 ops/ms
Iteration   3: 9.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.242 ±(99.9%) 1.191 ops/ms [Average]
  (min, avg, max) = (9.170, 9.242, 9.298), stdev = 0.065
  CI (99.9%): [8.050, 10.433] (assumes normal distribution)


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
# Warmup Iteration   1: 2.672 ops/ms
# Warmup Iteration   2: 7.249 ops/ms
# Warmup Iteration   3: 8.012 ops/ms
Iteration   1: 7.980 ops/ms
Iteration   2: 8.317 ops/ms
Iteration   3: 8.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.221 ±(99.9%) 3.845 ops/ms [Average]
  (min, avg, max) = (7.980, 8.221, 8.367), stdev = 0.211
  CI (99.9%): [4.376, 12.066] (assumes normal distribution)


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
# Warmup Iteration   1: 9.925 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.767 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.003 ms/op
Iteration   1: 3.424 ±(99.9%) 0.005 ms/op
Iteration   2: 3.401 ±(99.9%) 0.009 ms/op
Iteration   3: 3.241 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.355 ±(99.9%) 1.817 ms/op [Average]
  (min, avg, max) = (3.241, 3.355, 3.424), stdev = 0.100
  CI (99.9%): [1.538, 5.172] (assumes normal distribution)


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
# Warmup Iteration   1: 8.430 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.657 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.006 ms/op
Iteration   1: 3.313 ±(99.9%) 0.006 ms/op
Iteration   2: 3.282 ±(99.9%) 0.006 ms/op
Iteration   3: 3.157 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.251 ±(99.9%) 1.506 ms/op [Average]
  (min, avg, max) = (3.157, 3.251, 3.313), stdev = 0.083
  CI (99.9%): [1.744, 4.757] (assumes normal distribution)


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
# Warmup Iteration   1: 9.574 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.004 ms/op
Iteration   1: 3.343 ±(99.9%) 0.011 ms/op
Iteration   2: 3.411 ±(99.9%) 0.005 ms/op
Iteration   3: 3.386 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.380 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (3.343, 3.380, 3.411), stdev = 0.035
  CI (99.9%): [2.749, 4.010] (assumes normal distribution)


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
# Warmup Iteration   1: 11.181 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.405 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.008 ms/op
Iteration   1: 3.988 ±(99.9%) 0.011 ms/op
Iteration   2: 3.876 ±(99.9%) 0.010 ms/op
Iteration   3: 4.028 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.964 ±(99.9%) 1.442 ms/op [Average]
  (min, avg, max) = (3.876, 3.964, 4.028), stdev = 0.079
  CI (99.9%): [2.522, 5.406] (assumes normal distribution)


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
# Warmup Iteration   1: 8.726 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.582 ±(99.9%) 0.011 ms/op
Iteration   1: 3.393 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.401 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  18.232 ms/op
                 createUser·p0.9999: 21.617 ms/op
                 createUser·p1.00:   22.479 ms/op

Iteration   2: 3.422 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  20.072 ms/op
                 createUser·p0.9999: 22.140 ms/op
                 createUser·p1.00:   22.610 ms/op

Iteration   3: 3.334 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.352 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  19.661 ms/op
                 createUser·p0.9999: 30.631 ms/op
                 createUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283868
  mean =      3.383 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9060 
    [ 2.500,  5.000) = 269508 
    [ 5.000,  7.500) = 4378 
    [ 7.500, 10.000) = 430 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 194 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     19.038 ms/op
     p(99.9900) =     27.381 ms/op
     p(99.9990) =     31.571 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 8.202 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.557 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.009 ms/op
Iteration   1: 3.410 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.538 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   4.076 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   6.431 ms/op
                 existUser·p0.999:  10.568 ms/op
                 existUser·p0.9999: 22.368 ms/op
                 existUser·p1.00:   23.036 ms/op

Iteration   2: 3.351 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.729 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  22.282 ms/op
                 existUser·p0.9999: 24.341 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   3: 3.268 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.324 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  11.403 ms/op
                 existUser·p0.9999: 26.057 ms/op
                 existUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287292
  mean =      3.342 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12832 
    [ 2.500,  5.000) = 264955 
    [ 5.000,  7.500) = 8678 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.324 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     10.650 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     26.251 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 8.383 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.011 ms/op
Iteration   1: 3.451 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.688 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   6.869 ms/op
                 getUser·p0.999:  20.218 ms/op
                 getUser·p0.9999: 22.544 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   2: 3.347 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  20.134 ms/op
                 getUser·p0.9999: 26.688 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   3: 3.446 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.151 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  18.151 ms/op
                 getUser·p0.9999: 31.374 ms/op
                 getUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280940
  mean =      3.414 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6282 
    [ 2.500,  5.000) = 266285 
    [ 5.000,  7.500) = 7313 
    [ 7.500, 10.000) = 624 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 143 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     18.680 ms/op
     p(99.9900) =     28.451 ms/op
     p(99.9990) =     31.699 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 10.594 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.260 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.194 ±(99.9%) 0.014 ms/op
Iteration   1: 4.006 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.987 ms/op
                 listUser·p0.999:  17.975 ms/op
                 listUser·p0.9999: 26.411 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 4.018 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.367 ms/op
                 listUser·p0.999:  14.713 ms/op
                 listUser·p0.9999: 19.466 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   3: 3.949 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.661 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.123 ms/op
                 listUser·p0.9999: 16.022 ms/op
                 listUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240371
  mean =      3.991 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 233028 
    [ 5.000,  7.500) = 4972 
    [ 7.500, 10.000) = 1599 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.661 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     14.795 ms/op
     p(99.9900) =     25.034 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.288 ± 4.183  ops/ms
ClientPb.existUser                       thrpt       3   9.981 ± 4.952  ops/ms
ClientPb.getUser                         thrpt       3   9.242 ± 1.191  ops/ms
ClientPb.listUser                        thrpt       3   8.221 ± 3.845  ops/ms
ClientPb.createUser                       avgt       3   3.355 ± 1.817   ms/op
ClientPb.existUser                        avgt       3   3.251 ± 1.506   ms/op
ClientPb.getUser                          avgt       3   3.380 ± 0.630   ms/op
ClientPb.listUser                         avgt       3   3.964 ± 1.442   ms/op
ClientPb.createUser                     sample  283868   3.383 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.253           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.137           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.669           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.038           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.381           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.687           ms/op
ClientPb.existUser                      sample  287292   3.342 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.324           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.506           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.650           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.068           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.509           ms/op
ClientPb.getUser                        sample  280940   3.414 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.819           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.398           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.680           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.451           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.850           ms/op
ClientPb.listUser                       sample  240371   3.991 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.661           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.406           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.795           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.034           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.394           ms/op
