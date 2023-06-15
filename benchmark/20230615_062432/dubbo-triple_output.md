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
# Warmup Iteration   1: 2.382 ops/ms
# Warmup Iteration   2: 6.054 ops/ms
# Warmup Iteration   3: 9.202 ops/ms
Iteration   1: 9.903 ops/ms
Iteration   2: 9.661 ops/ms
Iteration   3: 9.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.793 ±(99.9%) 2.229 ops/ms [Average]
  (min, avg, max) = (9.661, 9.793, 9.903), stdev = 0.122
  CI (99.9%): [7.564, 12.022] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.674 ops/ms
# Warmup Iteration   2: 9.197 ops/ms
# Warmup Iteration   3: 9.593 ops/ms
Iteration   1: 10.582 ops/ms
Iteration   2: 9.777 ops/ms
Iteration   3: 10.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.330 ±(99.9%) 8.760 ops/ms [Average]
  (min, avg, max) = (9.777, 10.330, 10.632), stdev = 0.480
  CI (99.9%): [1.570, 19.091] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.895 ops/ms
# Warmup Iteration   2: 9.215 ops/ms
# Warmup Iteration   3: 9.721 ops/ms
Iteration   1: 9.817 ops/ms
Iteration   2: 10.029 ops/ms
Iteration   3: 10.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.054 ±(99.9%) 4.574 ops/ms [Average]
  (min, avg, max) = (9.817, 10.054, 10.316), stdev = 0.251
  CI (99.9%): [5.480, 14.628] (assumes normal distribution)


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
# Warmup Iteration   1: 3.385 ops/ms
# Warmup Iteration   2: 7.786 ops/ms
# Warmup Iteration   3: 8.128 ops/ms
Iteration   1: 8.500 ops/ms
Iteration   2: 8.571 ops/ms
Iteration   3: 8.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.562 ±(99.9%) 1.059 ops/ms [Average]
  (min, avg, max) = (8.500, 8.562, 8.615), stdev = 0.058
  CI (99.9%): [7.503, 9.622] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.267 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.002 ms/op
Iteration   1: 3.134 ±(99.9%) 0.005 ms/op
Iteration   2: 3.332 ±(99.9%) 0.003 ms/op
Iteration   3: 3.227 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.231 ±(99.9%) 1.806 ms/op [Average]
  (min, avg, max) = (3.134, 3.231, 3.332), stdev = 0.099
  CI (99.9%): [1.425, 5.038] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.327 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.004 ms/op
Iteration   1: 3.110 ±(99.9%) 0.004 ms/op
Iteration   2: 3.036 ±(99.9%) 0.004 ms/op
Iteration   3: 3.116 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.087 ±(99.9%) 0.813 ms/op [Average]
  (min, avg, max) = (3.036, 3.087, 3.116), stdev = 0.045
  CI (99.9%): [2.274, 3.901] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.086 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.417 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.006 ms/op
Iteration   1: 3.399 ±(99.9%) 0.007 ms/op
Iteration   2: 3.312 ±(99.9%) 0.003 ms/op
Iteration   3: 3.183 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.298 ±(99.9%) 1.978 ms/op [Average]
  (min, avg, max) = (3.183, 3.298, 3.399), stdev = 0.108
  CI (99.9%): [1.320, 5.276] (assumes normal distribution)


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
# Warmup Iteration   1: 8.745 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.004 ms/op
Iteration   1: 3.752 ±(99.9%) 0.009 ms/op
Iteration   2: 3.777 ±(99.9%) 0.006 ms/op
Iteration   3: 3.733 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.754 ±(99.9%) 0.403 ms/op [Average]
  (min, avg, max) = (3.733, 3.754, 3.777), stdev = 0.022
  CI (99.9%): [3.351, 4.157] (assumes normal distribution)


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
# Warmup Iteration   1: 7.508 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.663 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.008 ms/op
Iteration   1: 3.366 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.845 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  18.383 ms/op
                 createUser·p0.9999: 26.116 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   2: 3.289 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  12.241 ms/op
                 createUser·p0.9999: 22.193 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   3: 3.174 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  9.601 ms/op
                 createUser·p0.9999: 19.038 ms/op
                 createUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293189
  mean =      3.274 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22076 
    [ 2.500,  5.000) = 265151 
    [ 5.000,  7.500) = 5076 
    [ 7.500, 10.000) = 548 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     11.227 ms/op
     p(99.9900) =     23.550 ms/op
     p(99.9990) =     26.610 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.154 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.424 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.009 ms/op
Iteration   1: 3.058 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.047 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   5.195 ms/op
                 existUser·p0.999:  8.367 ms/op
                 existUser·p0.9999: 21.055 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   2: 3.169 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.036 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  13.304 ms/op
                 existUser·p0.9999: 25.887 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   3: 3.093 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.595 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  13.132 ms/op
                 existUser·p0.9999: 21.735 ms/op
                 existUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308931
  mean =      3.106 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16178 
    [ 2.500,  5.000) = 287898 
    [ 5.000,  7.500) = 3919 
    [ 7.500, 10.000) = 368 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     13.029 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     26.486 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 7.572 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.542 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.010 ms/op
Iteration   1: 3.357 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.845 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  16.955 ms/op
                 getUser·p0.9999: 21.913 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.766 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  15.286 ms/op
                 getUser·p0.9999: 25.190 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   3: 3.320 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  18.693 ms/op
                 getUser·p0.9999: 21.823 ms/op
                 getUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292342
  mean =      3.280 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12502 
    [ 2.500,  5.000) = 270337 
    [ 5.000,  7.500) = 8406 
    [ 7.500, 10.000) = 651 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     17.748 ms/op
     p(99.9900) =     23.323 ms/op
     p(99.9990) =     25.501 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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
# Warmup Iteration   1: 9.348 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.011 ms/op
Iteration   1: 3.699 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.647 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  14.939 ms/op
                 listUser·p0.9999: 22.568 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   2: 3.844 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  14.991 ms/op
                 listUser·p0.9999: 16.843 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   3: 3.807 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  12.583 ms/op
                 listUser·p0.9999: 17.498 ms/op
                 listUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253711
  mean =      3.782 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 243491 
    [ 5.000,  7.500) = 8092 
    [ 7.500, 10.000) = 1433 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 268 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.647 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     21.025 ms/op
     p(99.9990) =     22.854 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.793 ± 2.229  ops/ms
ClientPb.existUser                       thrpt       3  10.330 ± 8.760  ops/ms
ClientPb.getUser                         thrpt       3  10.054 ± 4.574  ops/ms
ClientPb.listUser                        thrpt       3   8.562 ± 1.059  ops/ms
ClientPb.createUser                       avgt       3   3.231 ± 1.806   ms/op
ClientPb.existUser                        avgt       3   3.087 ± 0.813   ms/op
ClientPb.getUser                          avgt       3   3.298 ± 1.978   ms/op
ClientPb.listUser                         avgt       3   3.754 ± 0.403   ms/op
ClientPb.createUser                     sample  293189   3.274 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.845           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.227           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.550           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.804           ms/op
ClientPb.existUser                      sample  308931   3.106 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.036           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.029           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.002           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.968           ms/op
ClientPb.getUser                        sample  292342   3.280 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.126           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.357           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.748           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.323           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.625           ms/op
ClientPb.listUser                       sample  253711   3.782 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.647           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.141           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.176           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.057           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.025           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.298           ms/op
