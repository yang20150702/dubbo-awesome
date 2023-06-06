# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.324 ops/ms
# Warmup Iteration   2: 6.088 ops/ms
# Warmup Iteration   3: 8.878 ops/ms
Iteration   1: 9.014 ops/ms
Iteration   2: 9.539 ops/ms
Iteration   3: 9.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.394 ±(99.9%) 6.073 ops/ms [Average]
  (min, avg, max) = (9.014, 9.394, 9.631), stdev = 0.333
  CI (99.9%): [3.321, 15.468] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.243 ops/ms
# Warmup Iteration   2: 9.069 ops/ms
# Warmup Iteration   3: 9.530 ops/ms
Iteration   1: 9.964 ops/ms
Iteration   2: 9.727 ops/ms
Iteration   3: 9.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.765 ±(99.9%) 3.336 ops/ms [Average]
  (min, avg, max) = (9.604, 9.765, 9.964), stdev = 0.183
  CI (99.9%): [6.429, 13.102] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.987 ops/ms
# Warmup Iteration   2: 7.727 ops/ms
# Warmup Iteration   3: 9.547 ops/ms
Iteration   1: 9.311 ops/ms
Iteration   2: 9.523 ops/ms
Iteration   3: 9.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.431 ±(99.9%) 1.987 ops/ms [Average]
  (min, avg, max) = (9.311, 9.431, 9.523), stdev = 0.109
  CI (99.9%): [7.445, 11.418] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.204 ops/ms
# Warmup Iteration   2: 7.310 ops/ms
# Warmup Iteration   3: 7.728 ops/ms
Iteration   1: 8.122 ops/ms
Iteration   2: 7.911 ops/ms
Iteration   3: 8.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.112 ±(99.9%) 3.589 ops/ms [Average]
  (min, avg, max) = (7.911, 8.112, 8.304), stdev = 0.197
  CI (99.9%): [4.523, 11.701] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.933 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.834 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.010 ms/op
Iteration   1: 3.390 ±(99.9%) 0.009 ms/op
Iteration   2: 3.251 ±(99.9%) 0.011 ms/op
Iteration   3: 3.498 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.380 ±(99.9%) 2.263 ms/op [Average]
  (min, avg, max) = (3.251, 3.380, 3.498), stdev = 0.124
  CI (99.9%): [1.117, 5.643] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.964 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.006 ms/op
Iteration   1: 3.234 ±(99.9%) 0.010 ms/op
Iteration   2: 3.231 ±(99.9%) 0.008 ms/op
Iteration   3: 3.266 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.244 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (3.231, 3.244, 3.266), stdev = 0.019
  CI (99.9%): [2.895, 3.592] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.201 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.522 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.007 ms/op
Iteration   1: 3.399 ±(99.9%) 0.009 ms/op
Iteration   2: 3.371 ±(99.9%) 0.006 ms/op
Iteration   3: 3.413 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.394 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (3.371, 3.394, 3.413), stdev = 0.021
  CI (99.9%): [3.007, 3.782] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.697 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.346 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.018 ±(99.9%) 0.009 ms/op
Iteration   1: 3.832 ±(99.9%) 0.014 ms/op
Iteration   2: 3.848 ±(99.9%) 0.017 ms/op
Iteration   3: 3.996 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.892 ±(99.9%) 1.648 ms/op [Average]
  (min, avg, max) = (3.832, 3.892, 3.996), stdev = 0.090
  CI (99.9%): [2.245, 5.540] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.097 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.889 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.009 ms/op
Iteration   1: 3.367 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  18.417 ms/op
                 createUser·p0.9999: 20.873 ms/op
                 createUser·p1.00:   22.544 ms/op

Iteration   2: 3.472 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 21.037 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   3: 3.382 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.585 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.699 ms/op
                 createUser·p0.999:  20.200 ms/op
                 createUser·p0.9999: 25.199 ms/op
                 createUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281588
  mean =      3.406 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5738 
    [ 2.500,  5.000) = 268089 
    [ 5.000,  7.500) = 6437 
    [ 7.500, 10.000) = 782 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 213 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     24.669 ms/op
     p(99.9990) =     25.348 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.956 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.007 ms/op
Iteration   1: 3.187 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  12.120 ms/op
                 existUser·p0.9999: 22.479 ms/op
                 existUser·p1.00:   23.429 ms/op

Iteration   2: 3.405 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.286 ms/op
                 existUser·p0.99:   5.912 ms/op
                 existUser·p0.999:  19.542 ms/op
                 existUser·p0.9999: 27.316 ms/op
                 existUser·p1.00:   27.951 ms/op

Iteration   3: 3.371 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.464 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   4.026 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  16.126 ms/op
                 existUser·p0.9999: 23.937 ms/op
                 existUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289147
  mean =      3.318 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17043 
    [ 2.500,  5.000) = 265707 
    [ 5.000,  7.500) = 5393 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 160 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     13.673 ms/op
     p(99.9900) =     25.890 ms/op
     p(99.9990) =     27.736 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.479 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.010 ms/op
Iteration   1: 3.464 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.552 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  14.074 ms/op
                 getUser·p0.9999: 27.984 ms/op
                 getUser·p1.00:   28.934 ms/op

Iteration   2: 3.350 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.807 ms/op
                 getUser·p0.999:  20.596 ms/op
                 getUser·p0.9999: 35.455 ms/op
                 getUser·p1.00:   36.176 ms/op

Iteration   3: 3.446 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.749 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  19.169 ms/op
                 getUser·p0.9999: 24.674 ms/op
                 getUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280701
  mean =      3.419 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10466 
    [ 2.500,  5.000) = 261081 
    [ 5.000,  7.500) = 7961 
    [ 7.500, 10.000) = 734 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     32.361 ms/op
     p(99.9990) =     35.926 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.693 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.288 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.063 ±(99.9%) 0.013 ms/op
Iteration   1: 4.138 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   7.873 ms/op
                 listUser·p0.999:  19.169 ms/op
                 listUser·p0.9999: 22.833 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   2: 3.937 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.255 ms/op
                 listUser·p0.999:  15.015 ms/op
                 listUser·p0.9999: 17.039 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 3.939 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  16.298 ms/op
                 listUser·p0.9999: 20.173 ms/op
                 listUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239624
  mean =      4.002 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 229190 
    [ 5.000,  7.500) = 8021 
    [ 7.500, 10.000) = 1523 
    [10.000, 12.500) = 400 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.269 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     16.423 ms/op
     p(99.9900) =     21.071 ms/op
     p(99.9990) =     23.272 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.394 ± 6.073  ops/ms
ClientPb.existUser                       thrpt       3   9.765 ± 3.336  ops/ms
ClientPb.getUser                         thrpt       3   9.431 ± 1.987  ops/ms
ClientPb.listUser                        thrpt       3   8.112 ± 3.589  ops/ms
ClientPb.createUser                       avgt       3   3.380 ± 2.263   ms/op
ClientPb.existUser                        avgt       3   3.244 ± 0.349   ms/op
ClientPb.getUser                          avgt       3   3.394 ± 0.387   ms/op
ClientPb.listUser                         avgt       3   3.892 ± 1.648   ms/op
ClientPb.createUser                     sample  281588   3.406 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.327           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.152           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.202           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.669           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.461           ms/op
ClientPb.existUser                      sample  289147   3.318 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.112           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.673           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.890           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.951           ms/op
ClientPb.getUser                        sample  280701   3.419 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.124           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.349           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.074           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.361           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.176           ms/op
ClientPb.listUser                       sample  239624   4.002 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.269           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.899           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.479           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.423           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.071           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.429           ms/op
