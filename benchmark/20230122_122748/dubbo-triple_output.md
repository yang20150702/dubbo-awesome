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
# Warmup Iteration   1: 2.316 ops/ms
# Warmup Iteration   2: 5.868 ops/ms
# Warmup Iteration   3: 7.994 ops/ms
Iteration   1: 9.449 ops/ms
Iteration   2: 9.166 ops/ms
Iteration   3: 9.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.307 ±(99.9%) 2.584 ops/ms [Average]
  (min, avg, max) = (9.166, 9.307, 9.449), stdev = 0.142
  CI (99.9%): [6.722, 11.891] (assumes normal distribution)


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
# Warmup Iteration   1: 3.038 ops/ms
# Warmup Iteration   2: 9.178 ops/ms
# Warmup Iteration   3: 9.348 ops/ms
Iteration   1: 9.455 ops/ms
Iteration   2: 9.848 ops/ms
Iteration   3: 9.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.765 ±(99.9%) 5.079 ops/ms [Average]
  (min, avg, max) = (9.455, 9.765, 9.993), stdev = 0.278
  CI (99.9%): [4.686, 14.844] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.384 ops/ms
# Warmup Iteration   2: 8.917 ops/ms
# Warmup Iteration   3: 9.005 ops/ms
Iteration   1: 9.519 ops/ms
Iteration   2: 9.440 ops/ms
Iteration   3: 9.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.518 ±(99.9%) 1.431 ops/ms [Average]
  (min, avg, max) = (9.440, 9.518, 9.597), stdev = 0.078
  CI (99.9%): [8.087, 10.949] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.025 ops/ms
# Warmup Iteration   2: 7.168 ops/ms
# Warmup Iteration   3: 7.807 ops/ms
Iteration   1: 7.835 ops/ms
Iteration   2: 8.373 ops/ms
Iteration   3: 7.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.057 ±(99.9%) 5.126 ops/ms [Average]
  (min, avg, max) = (7.835, 8.057, 8.373), stdev = 0.281
  CI (99.9%): [2.931, 13.183] (assumes normal distribution)


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
# Warmup Iteration   1: 10.226 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.652 ±(99.9%) 0.006 ms/op
Iteration   1: 3.447 ±(99.9%) 0.008 ms/op
Iteration   2: 3.446 ±(99.9%) 0.003 ms/op
Iteration   3: 3.328 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.407 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (3.328, 3.407, 3.447), stdev = 0.069
  CI (99.9%): [2.156, 4.658] (assumes normal distribution)


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
# Warmup Iteration   1: 8.366 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.009 ms/op
Iteration   1: 3.324 ±(99.9%) 0.010 ms/op
Iteration   2: 3.391 ±(99.9%) 0.010 ms/op
Iteration   3: 3.280 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.332 ±(99.9%) 1.018 ms/op [Average]
  (min, avg, max) = (3.280, 3.332, 3.391), stdev = 0.056
  CI (99.9%): [2.314, 4.350] (assumes normal distribution)


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
# Warmup Iteration   1: 9.120 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.002 ms/op
Iteration   1: 3.524 ±(99.9%) 0.006 ms/op
Iteration   2: 3.494 ±(99.9%) 0.003 ms/op
Iteration   3: 3.489 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.502 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (3.489, 3.502, 3.524), stdev = 0.019
  CI (99.9%): [3.156, 3.848] (assumes normal distribution)


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
# Warmup Iteration   1: 10.248 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.005 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.005 ms/op
Iteration   1: 4.118 ±(99.9%) 0.010 ms/op
Iteration   2: 4.132 ±(99.9%) 0.006 ms/op
Iteration   3: 4.008 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.086 ±(99.9%) 1.245 ms/op [Average]
  (min, avg, max) = (4.008, 4.086, 4.132), stdev = 0.068
  CI (99.9%): [2.841, 5.331] (assumes normal distribution)


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
# Warmup Iteration   1: 10.009 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.011 ms/op
Iteration   1: 3.424 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.497 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.072 ms/op
                 createUser·p0.999:  21.385 ms/op
                 createUser·p0.9999: 24.478 ms/op
                 createUser·p1.00:   24.707 ms/op

Iteration   2: 3.383 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.972 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  22.621 ms/op
                 createUser·p0.9999: 24.609 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   3: 3.443 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.333 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   5.458 ms/op
                 createUser·p0.999:  17.535 ms/op
                 createUser·p0.9999: 25.531 ms/op
                 createUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280779
  mean =      3.417 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10013 
    [ 2.500,  5.000) = 265068 
    [ 5.000,  7.500) = 4602 
    [ 7.500, 10.000) = 635 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 199 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     19.125 ms/op
     p(99.9900) =     24.609 ms/op
     p(99.9990) =     26.286 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 8.391 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
Iteration   1: 3.288 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  9.037 ms/op
                 existUser·p0.9999: 23.208 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 3.292 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  10.104 ms/op
                 existUser·p0.9999: 25.821 ms/op
                 existUser·p1.00:   27.132 ms/op

Iteration   3: 3.419 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.272 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  13.025 ms/op
                 existUser·p0.9999: 29.883 ms/op
                 existUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288049
  mean =      3.332 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18691 
    [ 2.500,  5.000) = 263897 
    [ 5.000,  7.500) = 4538 
    [ 7.500, 10.000) = 577 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     13.008 ms/op
     p(99.9900) =     28.324 ms/op
     p(99.9990) =     30.736 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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
# Warmup Iteration   1: 8.638 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.010 ms/op
Iteration   1: 3.456 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  20.887 ms/op
                 getUser·p0.9999: 23.027 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   2: 3.305 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  16.189 ms/op
                 getUser·p0.9999: 25.690 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   3: 3.489 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  14.231 ms/op
                 getUser·p0.9999: 24.041 ms/op
                 getUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280872
  mean =      3.415 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5102 
    [ 2.500,  5.000) = 266873 
    [ 5.000,  7.500) = 7690 
    [ 7.500, 10.000) = 826 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     14.389 ms/op
     p(99.9900) =     24.901 ms/op
     p(99.9990) =     26.463 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 10.372 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.289 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.013 ms/op
Iteration   1: 4.034 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  15.830 ms/op
                 listUser·p0.9999: 21.299 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   2: 4.140 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.806 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   8.184 ms/op
                 listUser·p0.999:  15.854 ms/op
                 listUser·p0.9999: 20.080 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   3: 4.049 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  13.911 ms/op
                 listUser·p0.9999: 17.891 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235704
  mean =      4.074 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 223797 
    [ 5.000,  7.500) = 8843 
    [ 7.500, 10.000) = 2216 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 256 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.930 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     20.560 ms/op
     p(99.9990) =     22.345 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.307 ± 2.584  ops/ms
ClientPb.existUser                       thrpt       3   9.765 ± 5.079  ops/ms
ClientPb.getUser                         thrpt       3   9.518 ± 1.431  ops/ms
ClientPb.listUser                        thrpt       3   8.057 ± 5.126  ops/ms
ClientPb.createUser                       avgt       3   3.407 ± 1.251   ms/op
ClientPb.existUser                        avgt       3   3.332 ± 1.018   ms/op
ClientPb.getUser                          avgt       3   3.502 ± 0.346   ms/op
ClientPb.listUser                         avgt       3   4.086 ± 1.245   ms/op
ClientPb.createUser                     sample  280779   3.417 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.333           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.800           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.125           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.609           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.444           ms/op
ClientPb.existUser                      sample  288049   3.332 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.130           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.857           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.008           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.324           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.425           ms/op
ClientPb.getUser                        sample  280872   3.415 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.332           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.389           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.901           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.673           ms/op
ClientPb.listUser                       sample  235704   4.074 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.540           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.005           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.270           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.560           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.479           ms/op
