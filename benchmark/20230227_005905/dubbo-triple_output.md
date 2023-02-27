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
# Warmup Iteration   1: 2.186 ops/ms
# Warmup Iteration   2: 6.156 ops/ms
# Warmup Iteration   3: 8.706 ops/ms
Iteration   1: 9.218 ops/ms
Iteration   2: 9.221 ops/ms
Iteration   3: 9.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.294 ±(99.9%) 2.346 ops/ms [Average]
  (min, avg, max) = (9.218, 9.294, 9.443), stdev = 0.129
  CI (99.9%): [6.948, 11.640] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.955 ops/ms
# Warmup Iteration   2: 8.626 ops/ms
# Warmup Iteration   3: 9.488 ops/ms
Iteration   1: 9.577 ops/ms
Iteration   2: 9.946 ops/ms
Iteration   3: 9.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.714 ±(99.9%) 3.688 ops/ms [Average]
  (min, avg, max) = (9.577, 9.714, 9.946), stdev = 0.202
  CI (99.9%): [6.027, 13.402] (assumes normal distribution)


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
# Warmup Iteration   1: 3.147 ops/ms
# Warmup Iteration   2: 8.373 ops/ms
# Warmup Iteration   3: 9.027 ops/ms
Iteration   1: 9.571 ops/ms
Iteration   2: 9.282 ops/ms
Iteration   3: 9.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.304 ±(99.9%) 4.700 ops/ms [Average]
  (min, avg, max) = (9.058, 9.304, 9.571), stdev = 0.258
  CI (99.9%): [4.604, 14.003] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.559 ops/ms
# Warmup Iteration   2: 7.122 ops/ms
# Warmup Iteration   3: 7.945 ops/ms
Iteration   1: 7.889 ops/ms
Iteration   2: 8.339 ops/ms
Iteration   3: 7.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.044 ±(99.9%) 4.669 ops/ms [Average]
  (min, avg, max) = (7.889, 8.044, 8.339), stdev = 0.256
  CI (99.9%): [3.375, 12.712] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.626 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.668 ±(99.9%) 0.005 ms/op
Iteration   1: 3.378 ±(99.9%) 0.008 ms/op
Iteration   2: 3.358 ±(99.9%) 0.009 ms/op
Iteration   3: 3.386 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.374 ±(99.9%) 0.261 ms/op [Average]
  (min, avg, max) = (3.358, 3.374, 3.386), stdev = 0.014
  CI (99.9%): [3.113, 3.636] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.966 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.006 ms/op
Iteration   1: 3.230 ±(99.9%) 0.009 ms/op
Iteration   2: 3.327 ±(99.9%) 0.003 ms/op
Iteration   3: 3.282 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.280 ±(99.9%) 0.890 ms/op [Average]
  (min, avg, max) = (3.230, 3.280, 3.327), stdev = 0.049
  CI (99.9%): [2.390, 4.169] (assumes normal distribution)


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
# Warmup Iteration   1: 10.738 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.007 ms/op
Iteration   1: 3.321 ±(99.9%) 0.008 ms/op
Iteration   2: 3.459 ±(99.9%) 0.005 ms/op
Iteration   3: 3.417 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.399 ±(99.9%) 1.290 ms/op [Average]
  (min, avg, max) = (3.321, 3.399, 3.459), stdev = 0.071
  CI (99.9%): [2.109, 4.689] (assumes normal distribution)


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
# Warmup Iteration   1: 10.267 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.013 ms/op
Iteration   1: 4.101 ±(99.9%) 0.009 ms/op
Iteration   2: 4.010 ±(99.9%) 0.012 ms/op
Iteration   3: 4.013 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.041 ±(99.9%) 0.949 ms/op [Average]
  (min, avg, max) = (4.010, 4.041, 4.101), stdev = 0.052
  CI (99.9%): [3.093, 4.990] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.432 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.634 ±(99.9%) 0.013 ms/op
Iteration   1: 3.446 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.651 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  18.448 ms/op
                 createUser·p0.9999: 20.944 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   2: 3.493 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.300 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  19.857 ms/op
                 createUser·p0.9999: 22.479 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   3: 3.405 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.626 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  18.711 ms/op
                 createUser·p0.9999: 27.447 ms/op
                 createUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278378
  mean =      3.448 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2318 
    [ 2.500,  5.000) = 268493 
    [ 5.000,  7.500) = 6131 
    [ 7.500, 10.000) = 968 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     18.600 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     28.155 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 8.206 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.010 ms/op
Iteration   1: 3.312 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.041 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  9.385 ms/op
                 existUser·p0.9999: 27.570 ms/op
                 existUser·p1.00:   28.148 ms/op

Iteration   2: 3.322 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.602 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   6.017 ms/op
                 existUser·p0.999:  19.196 ms/op
                 existUser·p0.9999: 29.786 ms/op
                 existUser·p1.00:   30.605 ms/op

Iteration   3: 3.259 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  12.138 ms/op
                 existUser·p0.9999: 32.375 ms/op
                 existUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291018
  mean =      3.298 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15179 
    [ 2.500,  5.000) = 269259 
    [ 5.000,  7.500) = 5467 
    [ 7.500, 10.000) = 728 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     11.206 ms/op
     p(99.9900) =     30.635 ms/op
     p(99.9990) =     32.473 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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
# Warmup Iteration   1: 9.705 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.766 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.010 ms/op
Iteration   1: 3.395 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   6.055 ms/op
                 getUser·p0.999:  18.016 ms/op
                 getUser·p0.9999: 22.858 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   2: 3.390 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   6.697 ms/op
                 getUser·p0.999:  10.109 ms/op
                 getUser·p0.9999: 23.579 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   3: 3.515 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  21.982 ms/op
                 getUser·p0.9999: 25.749 ms/op
                 getUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279472
  mean =      3.433 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6896 
    [ 2.500,  5.000) = 265387 
    [ 5.000,  7.500) = 5897 
    [ 7.500, 10.000) = 820 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     16.172 ms/op
     p(99.9900) =     24.381 ms/op
     p(99.9990) =     26.025 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 10.787 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.402 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.014 ms/op
Iteration   1: 4.094 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  21.095 ms/op
                 listUser·p0.9999: 26.483 ms/op
                 listUser·p1.00:   27.099 ms/op

Iteration   2: 3.932 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  15.038 ms/op
                 listUser·p0.9999: 18.768 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   3: 3.872 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  14.495 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242165
  mean =      3.964 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 235567 
    [ 5.000,  7.500) = 4492 
    [ 7.500, 10.000) = 1118 
    [10.000, 12.500) = 443 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      2.085 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     16.048 ms/op
     p(99.9900) =     25.060 ms/op
     p(99.9990) =     27.058 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.294 ± 2.346  ops/ms
ClientPb.existUser                       thrpt       3   9.714 ± 3.688  ops/ms
ClientPb.getUser                         thrpt       3   9.304 ± 4.700  ops/ms
ClientPb.listUser                        thrpt       3   8.044 ± 4.669  ops/ms
ClientPb.createUser                       avgt       3   3.374 ± 0.261   ms/op
ClientPb.existUser                        avgt       3   3.280 ± 0.890   ms/op
ClientPb.getUser                          avgt       3   3.399 ± 1.290   ms/op
ClientPb.listUser                         avgt       3   4.041 ± 0.949   ms/op
ClientPb.createUser                     sample  278378   3.448 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.300           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.308           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.600           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.723           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.180           ms/op
ClientPb.existUser                      sample  291018   3.298 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.041           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.067           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.013           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.206           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.635           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.571           ms/op
ClientPb.getUser                        sample  279472   3.433 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.073           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.186           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.316           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.172           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.381           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.182           ms/op
ClientPb.listUser                       sample  242165   3.964 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.085           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.193           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.048           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.060           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.099           ms/op
