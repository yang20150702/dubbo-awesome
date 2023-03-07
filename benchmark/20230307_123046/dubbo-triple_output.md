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
# Warmup Iteration   1: 2.204 ops/ms
# Warmup Iteration   2: 5.654 ops/ms
# Warmup Iteration   3: 8.242 ops/ms
Iteration   1: 9.207 ops/ms
Iteration   2: 9.275 ops/ms
Iteration   3: 9.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.169 ±(99.9%) 2.357 ops/ms [Average]
  (min, avg, max) = (9.025, 9.169, 9.275), stdev = 0.129
  CI (99.9%): [6.812, 11.526] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.886 ops/ms
# Warmup Iteration   2: 8.781 ops/ms
# Warmup Iteration   3: 9.562 ops/ms
Iteration   1: 10.070 ops/ms
Iteration   2: 9.917 ops/ms
Iteration   3: 9.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.932 ±(99.9%) 2.400 ops/ms [Average]
  (min, avg, max) = (9.808, 9.932, 10.070), stdev = 0.132
  CI (99.9%): [7.531, 12.332] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.436 ops/ms
# Warmup Iteration   2: 8.733 ops/ms
# Warmup Iteration   3: 9.326 ops/ms
Iteration   1: 9.647 ops/ms
Iteration   2: 9.444 ops/ms
Iteration   3: 9.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.616 ±(99.9%) 2.894 ops/ms [Average]
  (min, avg, max) = (9.444, 9.616, 9.757), stdev = 0.159
  CI (99.9%): [6.722, 12.510] (assumes normal distribution)


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
# Warmup Iteration   1: 2.865 ops/ms
# Warmup Iteration   2: 7.407 ops/ms
# Warmup Iteration   3: 7.993 ops/ms
Iteration   1: 8.068 ops/ms
Iteration   2: 8.105 ops/ms
Iteration   3: 8.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.181 ±(99.9%) 3.002 ops/ms [Average]
  (min, avg, max) = (8.068, 8.181, 8.370), stdev = 0.165
  CI (99.9%): [5.179, 11.184] (assumes normal distribution)


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
# Warmup Iteration   1: 10.334 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.857 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.011 ms/op
Iteration   1: 3.417 ±(99.9%) 0.007 ms/op
Iteration   2: 3.417 ±(99.9%) 0.004 ms/op
Iteration   3: 3.320 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.385 ±(99.9%) 1.021 ms/op [Average]
  (min, avg, max) = (3.320, 3.385, 3.417), stdev = 0.056
  CI (99.9%): [2.364, 4.405] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.453 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.003 ms/op
Iteration   1: 3.255 ±(99.9%) 0.010 ms/op
Iteration   2: 3.400 ±(99.9%) 0.005 ms/op
Iteration   3: 3.330 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.328 ±(99.9%) 1.321 ms/op [Average]
  (min, avg, max) = (3.255, 3.328, 3.400), stdev = 0.072
  CI (99.9%): [2.007, 4.649] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.086 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.801 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.007 ms/op
Iteration   1: 3.344 ±(99.9%) 0.012 ms/op
Iteration   2: 3.424 ±(99.9%) 0.006 ms/op
Iteration   3: 3.441 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.403 ±(99.9%) 0.946 ms/op [Average]
  (min, avg, max) = (3.344, 3.403, 3.441), stdev = 0.052
  CI (99.9%): [2.457, 4.350] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.290 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.310 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.008 ms/op
Iteration   1: 4.033 ±(99.9%) 0.008 ms/op
Iteration   2: 4.073 ±(99.9%) 0.007 ms/op
Iteration   3: 3.941 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.016 ±(99.9%) 1.234 ms/op [Average]
  (min, avg, max) = (3.941, 4.016, 4.073), stdev = 0.068
  CI (99.9%): [2.782, 5.250] (assumes normal distribution)


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
# Warmup Iteration   1: 9.398 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.010 ms/op
Iteration   1: 3.457 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.466 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  19.742 ms/op
                 createUser·p0.9999: 22.667 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   2: 3.349 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.409 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  22.149 ms/op
                 createUser·p0.9999: 25.934 ms/op
                 createUser·p1.00:   26.968 ms/op

Iteration   3: 3.488 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  17.934 ms/op
                 createUser·p0.9999: 28.410 ms/op
                 createUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279712
  mean =      3.430 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6121 
    [ 2.500,  5.000) = 265243 
    [ 5.000,  7.500) = 7141 
    [ 7.500, 10.000) = 774 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     17.999 ms/op
     p(99.9900) =     26.969 ms/op
     p(99.9990) =     29.393 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 9.315 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.008 ms/op
Iteration   1: 3.256 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.436 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  10.076 ms/op
                 existUser·p0.9999: 20.295 ms/op
                 existUser·p1.00:   20.677 ms/op

Iteration   2: 3.394 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.374 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  19.719 ms/op
                 existUser·p0.9999: 24.281 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   3: 3.365 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  8.396 ms/op
                 existUser·p0.9999: 34.996 ms/op
                 existUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287649
  mean =      3.337 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16881 
    [ 2.500,  5.000) = 264109 
    [ 5.000,  7.500) = 5647 
    [ 7.500, 10.000) = 642 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     11.993 ms/op
     p(99.9900) =     33.136 ms/op
     p(99.9990) =     35.258 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 9.321 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.544 ±(99.9%) 0.011 ms/op
Iteration   1: 3.468 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.857 ms/op
                 getUser·p0.999:  19.657 ms/op
                 getUser·p0.9999: 22.982 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   2: 3.316 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   5.005 ms/op
                 getUser·p0.999:  17.387 ms/op
                 getUser·p0.9999: 24.687 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   3: 3.430 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.483 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  12.170 ms/op
                 getUser·p0.9999: 24.434 ms/op
                 getUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281811
  mean =      3.404 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7214 
    [ 2.500,  5.000) = 267844 
    [ 5.000,  7.500) = 5535 
    [ 7.500, 10.000) = 779 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 146 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     15.911 ms/op
     p(99.9900) =     24.302 ms/op
     p(99.9990) =     25.735 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 10.993 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.335 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.013 ms/op
Iteration   1: 4.056 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.679 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  17.443 ms/op
                 listUser·p0.9999: 23.629 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   2: 3.940 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.093 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  14.738 ms/op
                 listUser·p0.9999: 20.644 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   3: 3.933 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  15.614 ms/op
                 listUser·p0.9999: 20.672 ms/op
                 listUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241445
  mean =      3.976 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 233458 
    [ 5.000,  7.500) = 5829 
    [ 7.500, 10.000) = 1325 
    [10.000, 12.500) = 291 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.189 ms/op
     p(99.9000) =     15.725 ms/op
     p(99.9900) =     22.376 ms/op
     p(99.9990) =     24.077 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.169 ± 2.357  ops/ms
ClientPb.existUser                       thrpt       3   9.932 ± 2.400  ops/ms
ClientPb.getUser                         thrpt       3   9.616 ± 2.894  ops/ms
ClientPb.listUser                        thrpt       3   8.181 ± 3.002  ops/ms
ClientPb.createUser                       avgt       3   3.385 ± 1.021   ms/op
ClientPb.existUser                        avgt       3   3.328 ± 1.321   ms/op
ClientPb.getUser                          avgt       3   3.403 ± 0.946   ms/op
ClientPb.listUser                         avgt       3   4.016 ± 1.234   ms/op
ClientPb.createUser                     sample  279712   3.430 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.403           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.432           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.332           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.999           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.969           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.590           ms/op
ClientPb.existUser                      sample  287649   3.337 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.662           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.993           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.136           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.848           ms/op
ClientPb.getUser                        sample  281811   3.404 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.051           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.141           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.300           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.911           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.302           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.149           ms/op
ClientPb.listUser                       sample  241445   3.976 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.266           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.189           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.725           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.376           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.347           ms/op
