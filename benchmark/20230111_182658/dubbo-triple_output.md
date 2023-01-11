# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.372 ops/ms
# Warmup Iteration   2: 5.611 ops/ms
# Warmup Iteration   3: 8.714 ops/ms
Iteration   1: 9.112 ops/ms
Iteration   2: 9.286 ops/ms
Iteration   3: 9.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.288 ±(99.9%) 3.222 ops/ms [Average]
  (min, avg, max) = (9.112, 9.288, 9.466), stdev = 0.177
  CI (99.9%): [6.066, 12.510] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.629 ops/ms
# Warmup Iteration   2: 8.957 ops/ms
# Warmup Iteration   3: 9.623 ops/ms
Iteration   1: 9.481 ops/ms
Iteration   2: 10.033 ops/ms
Iteration   3: 9.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.739 ±(99.9%) 5.064 ops/ms [Average]
  (min, avg, max) = (9.481, 9.739, 10.033), stdev = 0.278
  CI (99.9%): [4.675, 14.803] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.937 ops/ms
# Warmup Iteration   2: 8.060 ops/ms
# Warmup Iteration   3: 9.472 ops/ms
Iteration   1: 9.480 ops/ms
Iteration   2: 9.205 ops/ms
Iteration   3: 9.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.365 ±(99.9%) 2.602 ops/ms [Average]
  (min, avg, max) = (9.205, 9.365, 9.480), stdev = 0.143
  CI (99.9%): [6.762, 11.967] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.754 ops/ms
# Warmup Iteration   2: 7.160 ops/ms
# Warmup Iteration   3: 8.106 ops/ms
Iteration   1: 8.152 ops/ms
Iteration   2: 7.909 ops/ms
Iteration   3: 8.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.102 ±(99.9%) 3.179 ops/ms [Average]
  (min, avg, max) = (7.909, 8.102, 8.247), stdev = 0.174
  CI (99.9%): [4.923, 11.282] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.278 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.005 ms/op
Iteration   1: 3.353 ±(99.9%) 0.009 ms/op
Iteration   2: 3.544 ±(99.9%) 0.007 ms/op
Iteration   3: 3.373 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.423 ±(99.9%) 1.913 ms/op [Average]
  (min, avg, max) = (3.353, 3.423, 3.544), stdev = 0.105
  CI (99.9%): [1.510, 5.337] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.172 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.006 ms/op
Iteration   1: 3.309 ±(99.9%) 0.011 ms/op
Iteration   2: 3.340 ±(99.9%) 0.006 ms/op
Iteration   3: 3.269 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.306 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (3.269, 3.306, 3.340), stdev = 0.036
  CI (99.9%): [2.656, 3.955] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.460 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.559 ±(99.9%) 0.005 ms/op
Iteration   1: 3.475 ±(99.9%) 0.004 ms/op
Iteration   2: 3.381 ±(99.9%) 0.008 ms/op
Iteration   3: 3.356 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.404 ±(99.9%) 1.147 ms/op [Average]
  (min, avg, max) = (3.356, 3.404, 3.475), stdev = 0.063
  CI (99.9%): [2.257, 4.551] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.384 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.432 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.131 ±(99.9%) 0.008 ms/op
Iteration   1: 3.981 ±(99.9%) 0.011 ms/op
Iteration   2: 4.000 ±(99.9%) 0.010 ms/op
Iteration   3: 3.847 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.943 ±(99.9%) 1.517 ms/op [Average]
  (min, avg, max) = (3.847, 3.943, 4.000), stdev = 0.083
  CI (99.9%): [2.426, 5.459] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.131 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.010 ms/op
Iteration   1: 3.436 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  20.966 ms/op
                 createUser·p0.9999: 28.541 ms/op
                 createUser·p1.00:   31.031 ms/op

Iteration   2: 3.473 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  22.512 ms/op
                 createUser·p0.9999: 26.306 ms/op
                 createUser·p1.00:   27.558 ms/op

Iteration   3: 3.497 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  20.578 ms/op
                 createUser·p0.9999: 25.966 ms/op
                 createUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276716
  mean =      3.468 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11329 
    [ 2.500,  5.000) = 256446 
    [ 5.000,  7.500) = 7641 
    [ 7.500, 10.000) = 752 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 114 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     20.761 ms/op
     p(99.9900) =     27.558 ms/op
     p(99.9990) =     29.431 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.853 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.009 ms/op
Iteration   1: 3.217 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.446 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   5.046 ms/op
                 existUser·p0.999:  10.011 ms/op
                 existUser·p0.9999: 24.084 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   2: 3.341 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.657 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  21.507 ms/op
                 existUser·p0.9999: 29.636 ms/op
                 existUser·p1.00:   30.736 ms/op

Iteration   3: 3.350 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.442 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  20.840 ms/op
                 existUser·p0.9999: 26.196 ms/op
                 existUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290609
  mean =      3.302 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18264 
    [ 2.500,  5.000) = 267348 
    [ 5.000,  7.500) = 3855 
    [ 7.500, 10.000) = 548 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.442 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     18.297 ms/op
     p(99.9900) =     27.910 ms/op
     p(99.9990) =     30.525 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.808 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.012 ms/op
Iteration   1: 3.422 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.667 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  20.174 ms/op
                 getUser·p0.9999: 31.872 ms/op
                 getUser·p1.00:   33.817 ms/op

Iteration   2: 3.465 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.630 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  21.692 ms/op
                 getUser·p0.9999: 25.690 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   3: 3.418 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  15.816 ms/op
                 getUser·p0.9999: 23.025 ms/op
                 getUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279133
  mean =      3.435 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4268 
    [ 2.500,  5.000) = 268104 
    [ 5.000,  7.500) = 5406 
    [ 7.500, 10.000) = 985 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     16.663 ms/op
     p(99.9900) =     31.105 ms/op
     p(99.9990) =     32.174 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.531 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.406 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.013 ms/op
Iteration   1: 4.041 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  19.988 ms/op
                 listUser·p0.9999: 23.792 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   2: 4.006 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.054 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  15.146 ms/op
                 listUser·p0.9999: 17.171 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   3: 3.883 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.548 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.038 ms/op
                 listUser·p0.999:  14.119 ms/op
                 listUser·p0.9999: 22.799 ms/op
                 listUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241249
  mean =      3.976 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 232414 
    [ 5.000,  7.500) = 6618 
    [ 7.500, 10.000) = 1351 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.724 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     16.564 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     24.129 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.288 ± 3.222  ops/ms
ClientPb.existUser                       thrpt       3   9.739 ± 5.064  ops/ms
ClientPb.getUser                         thrpt       3   9.365 ± 2.602  ops/ms
ClientPb.listUser                        thrpt       3   8.102 ± 3.179  ops/ms
ClientPb.createUser                       avgt       3   3.423 ± 1.913   ms/op
ClientPb.existUser                        avgt       3   3.306 ± 0.650   ms/op
ClientPb.getUser                          avgt       3   3.404 ± 1.147   ms/op
ClientPb.listUser                         avgt       3   3.943 ± 1.517   ms/op
ClientPb.createUser                     sample  276716   3.468 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.055           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.359           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.480           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.761           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.558           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.031           ms/op
ClientPb.existUser                      sample  290609   3.302 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.442           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.895           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.562           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.297           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.910           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.736           ms/op
ClientPb.getUser                        sample  279133   3.435 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.735           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.431           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.663           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.105           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.817           ms/op
ClientPb.listUser                       sample  241249   3.976 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.724           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.324           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.564           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.774           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.248           ms/op
