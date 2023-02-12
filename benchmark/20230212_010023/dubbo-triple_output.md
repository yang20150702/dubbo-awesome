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
# Warmup Iteration   1: 2.183 ops/ms
# Warmup Iteration   2: 6.132 ops/ms
# Warmup Iteration   3: 8.998 ops/ms
Iteration   1: 9.612 ops/ms
Iteration   2: 9.296 ops/ms
Iteration   3: 9.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.373 ±(99.9%) 3.846 ops/ms [Average]
  (min, avg, max) = (9.212, 9.373, 9.612), stdev = 0.211
  CI (99.9%): [5.527, 13.219] (assumes normal distribution)


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
# Warmup Iteration   1: 3.542 ops/ms
# Warmup Iteration   2: 9.263 ops/ms
# Warmup Iteration   3: 9.532 ops/ms
Iteration   1: 9.616 ops/ms
Iteration   2: 9.957 ops/ms
Iteration   3: 9.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.740 ±(99.9%) 3.442 ops/ms [Average]
  (min, avg, max) = (9.616, 9.740, 9.957), stdev = 0.189
  CI (99.9%): [6.298, 13.181] (assumes normal distribution)


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
# Warmup Iteration   1: 3.011 ops/ms
# Warmup Iteration   2: 8.718 ops/ms
# Warmup Iteration   3: 9.364 ops/ms
Iteration   1: 9.223 ops/ms
Iteration   2: 9.710 ops/ms
Iteration   3: 9.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.399 ±(99.9%) 4.923 ops/ms [Average]
  (min, avg, max) = (9.223, 9.399, 9.710), stdev = 0.270
  CI (99.9%): [4.476, 14.322] (assumes normal distribution)


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
# Warmup Iteration   1: 2.884 ops/ms
# Warmup Iteration   2: 7.272 ops/ms
# Warmup Iteration   3: 7.906 ops/ms
Iteration   1: 8.195 ops/ms
Iteration   2: 8.038 ops/ms
Iteration   3: 8.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.185 ±(99.9%) 2.586 ops/ms [Average]
  (min, avg, max) = (8.038, 8.185, 8.321), stdev = 0.142
  CI (99.9%): [5.599, 10.771] (assumes normal distribution)


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
# Warmup Iteration   1: 9.927 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.766 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.535 ±(99.9%) 0.003 ms/op
Iteration   1: 3.447 ±(99.9%) 0.007 ms/op
Iteration   2: 3.304 ±(99.9%) 0.008 ms/op
Iteration   3: 3.307 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.352 ±(99.9%) 1.493 ms/op [Average]
  (min, avg, max) = (3.304, 3.352, 3.447), stdev = 0.082
  CI (99.9%): [1.860, 4.845] (assumes normal distribution)


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
# Warmup Iteration   1: 10.611 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.658 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.004 ms/op
Iteration   1: 3.245 ±(99.9%) 0.004 ms/op
Iteration   2: 3.209 ±(99.9%) 0.006 ms/op
Iteration   3: 3.353 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.269 ±(99.9%) 1.362 ms/op [Average]
  (min, avg, max) = (3.209, 3.269, 3.353), stdev = 0.075
  CI (99.9%): [1.907, 4.631] (assumes normal distribution)


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
# Warmup Iteration   1: 8.849 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.006 ms/op
Iteration   1: 3.309 ±(99.9%) 0.008 ms/op
Iteration   2: 3.291 ±(99.9%) 0.008 ms/op
Iteration   3: 3.251 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.283 ±(99.9%) 0.544 ms/op [Average]
  (min, avg, max) = (3.251, 3.283, 3.309), stdev = 0.030
  CI (99.9%): [2.739, 3.827] (assumes normal distribution)


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
# Warmup Iteration   1: 10.111 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.425 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.009 ms/op
Iteration   1: 3.949 ±(99.9%) 0.011 ms/op
Iteration   2: 3.842 ±(99.9%) 0.013 ms/op
Iteration   3: 3.921 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.904 ±(99.9%) 1.017 ms/op [Average]
  (min, avg, max) = (3.842, 3.904, 3.949), stdev = 0.056
  CI (99.9%): [2.887, 4.921] (assumes normal distribution)


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
# Warmup Iteration   1: 8.937 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.916 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.010 ms/op
Iteration   1: 3.391 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.675 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  19.565 ms/op
                 createUser·p0.9999: 22.348 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.476 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.381 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  21.363 ms/op
                 createUser·p0.9999: 29.295 ms/op
                 createUser·p1.00:   30.507 ms/op

Iteration   3: 3.503 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.495 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  20.364 ms/op
                 createUser·p0.9999: 23.036 ms/op
                 createUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277663
  mean =      3.456 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9118 
    [ 2.500,  5.000) = 261041 
    [ 5.000,  7.500) = 6171 
    [ 7.500, 10.000) = 866 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 172 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.381 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     20.032 ms/op
     p(99.9900) =     27.220 ms/op
     p(99.9990) =     30.121 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 7.333 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.391 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.010 ms/op
Iteration   1: 3.380 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.718 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  9.024 ms/op
                 existUser·p0.9999: 35.979 ms/op
                 existUser·p1.00:   36.831 ms/op

Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  9.994 ms/op
                 existUser·p0.9999: 24.707 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   3: 3.260 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.399 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.975 ms/op
                 existUser·p0.999:  14.450 ms/op
                 existUser·p0.9999: 31.550 ms/op
                 existUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290634
  mean =      3.299 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10987 
    [ 2.500,  5.000) = 274821 
    [ 5.000,  7.500) = 3970 
    [ 7.500, 10.000) = 481 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     12.081 ms/op
     p(99.9900) =     33.808 ms/op
     p(99.9990) =     36.641 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


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
# Warmup Iteration   1: 8.511 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.009 ms/op
Iteration   1: 3.563 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  9.849 ms/op
                 getUser·p0.9999: 23.561 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   2: 3.300 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  11.014 ms/op
                 getUser·p0.9999: 30.527 ms/op
                 getUser·p1.00:   31.031 ms/op

Iteration   3: 3.381 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  20.500 ms/op
                 getUser·p0.9999: 25.577 ms/op
                 getUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281396
  mean =      3.411 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9338 
    [ 2.500,  5.000) = 263494 
    [ 5.000,  7.500) = 7482 
    [ 7.500, 10.000) = 684 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     11.436 ms/op
     p(99.9900) =     28.897 ms/op
     p(99.9990) =     30.841 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 10.866 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.446 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.013 ms/op
Iteration   1: 3.920 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.632 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  18.186 ms/op
                 listUser·p0.9999: 22.801 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   2: 4.067 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   8.167 ms/op
                 listUser·p0.999:  17.727 ms/op
                 listUser·p0.9999: 19.857 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   3: 3.929 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  13.456 ms/op
                 listUser·p0.9999: 21.098 ms/op
                 listUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241682
  mean =      3.971 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 234079 
    [ 5.000,  7.500) = 5060 
    [ 7.500, 10.000) = 1646 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 284 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     15.565 ms/op
     p(99.9900) =     22.200 ms/op
     p(99.9990) =     23.284 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.373 ± 3.846  ops/ms
ClientPb.existUser                       thrpt       3   9.740 ± 3.442  ops/ms
ClientPb.getUser                         thrpt       3   9.399 ± 4.923  ops/ms
ClientPb.listUser                        thrpt       3   8.185 ± 2.586  ops/ms
ClientPb.createUser                       avgt       3   3.352 ± 1.493   ms/op
ClientPb.existUser                        avgt       3   3.269 ± 1.362   ms/op
ClientPb.getUser                          avgt       3   3.283 ± 0.544   ms/op
ClientPb.listUser                         avgt       3   3.904 ± 1.017   ms/op
ClientPb.createUser                     sample  277663   3.456 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.381           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.201           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.032           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.220           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.507           ms/op
ClientPb.existUser                      sample  290634   3.299 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.284           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.521           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.081           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.808           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.831           ms/op
ClientPb.getUser                        sample  281396   3.411 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.671           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.289           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.398           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.436           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.897           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.031           ms/op
ClientPb.listUser                       sample  241682   3.971 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.632           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.565           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.200           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.658           ms/op
