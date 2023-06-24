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
# Warmup Iteration   1: 2.367 ops/ms
# Warmup Iteration   2: 5.981 ops/ms
# Warmup Iteration   3: 9.243 ops/ms
Iteration   1: 9.959 ops/ms
Iteration   2: 9.655 ops/ms
Iteration   3: 10.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.997 ±(99.9%) 6.609 ops/ms [Average]
  (min, avg, max) = (9.655, 9.997, 10.377), stdev = 0.362
  CI (99.9%): [3.388, 16.606] (assumes normal distribution)


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
# Warmup Iteration   1: 3.802 ops/ms
# Warmup Iteration   2: 9.361 ops/ms
# Warmup Iteration   3: 9.909 ops/ms
Iteration   1: 10.046 ops/ms
Iteration   2: 10.324 ops/ms
Iteration   3: 10.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.229 ±(99.9%) 2.887 ops/ms [Average]
  (min, avg, max) = (10.046, 10.229, 10.324), stdev = 0.158
  CI (99.9%): [7.342, 13.116] (assumes normal distribution)


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
# Warmup Iteration   1: 3.540 ops/ms
# Warmup Iteration   2: 9.105 ops/ms
# Warmup Iteration   3: 9.886 ops/ms
Iteration   1: 10.007 ops/ms
Iteration   2: 10.375 ops/ms
Iteration   3: 10.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.212 ±(99.9%) 3.417 ops/ms [Average]
  (min, avg, max) = (10.007, 10.212, 10.375), stdev = 0.187
  CI (99.9%): [6.795, 13.629] (assumes normal distribution)


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
# Warmup Iteration   1: 3.160 ops/ms
# Warmup Iteration   2: 7.775 ops/ms
# Warmup Iteration   3: 8.468 ops/ms
Iteration   1: 8.580 ops/ms
Iteration   2: 8.608 ops/ms
Iteration   3: 8.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.575 ±(99.9%) 0.641 ops/ms [Average]
  (min, avg, max) = (8.538, 8.575, 8.608), stdev = 0.035
  CI (99.9%): [7.934, 9.216] (assumes normal distribution)


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
# Warmup Iteration   1: 7.993 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.593 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.005 ms/op
Iteration   1: 3.251 ±(99.9%) 0.007 ms/op
Iteration   2: 3.159 ±(99.9%) 0.007 ms/op
Iteration   3: 3.089 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.166 ±(99.9%) 1.478 ms/op [Average]
  (min, avg, max) = (3.089, 3.166, 3.251), stdev = 0.081
  CI (99.9%): [1.688, 4.645] (assumes normal distribution)


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
# Warmup Iteration   1: 7.225 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
Iteration   1: 3.041 ±(99.9%) 0.007 ms/op
Iteration   2: 3.087 ±(99.9%) 0.011 ms/op
Iteration   3: 2.978 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.035 ±(99.9%) 0.997 ms/op [Average]
  (min, avg, max) = (2.978, 3.035, 3.087), stdev = 0.055
  CI (99.9%): [2.038, 4.032] (assumes normal distribution)


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
# Warmup Iteration   1: 8.505 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.411 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.006 ms/op
Iteration   1: 3.154 ±(99.9%) 0.003 ms/op
Iteration   2: 3.199 ±(99.9%) 0.003 ms/op
Iteration   3: 3.105 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.153 ±(99.9%) 0.855 ms/op [Average]
  (min, avg, max) = (3.105, 3.153, 3.199), stdev = 0.047
  CI (99.9%): [2.298, 4.008] (assumes normal distribution)


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
# Warmup Iteration   1: 9.409 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.007 ms/op
Iteration   1: 3.707 ±(99.9%) 0.011 ms/op
Iteration   2: 3.654 ±(99.9%) 0.009 ms/op
Iteration   3: 3.689 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.683 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (3.654, 3.683, 3.707), stdev = 0.027
  CI (99.9%): [3.195, 4.172] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.882 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.711 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.180 ±(99.9%) 0.008 ms/op
Iteration   1: 3.116 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.260 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.269 ms/op
                 createUser·p0.95:   3.490 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  18.692 ms/op
                 createUser·p0.9999: 21.815 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.329 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  13.511 ms/op
                 createUser·p0.9999: 22.505 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   3: 3.133 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.657 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.269 ms/op
                 createUser·p0.95:   3.531 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  9.083 ms/op
                 createUser·p0.9999: 17.191 ms/op
                 createUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306383
  mean =      3.128 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23663 
    [ 2.500,  5.000) = 278203 
    [ 5.000,  7.500) = 3585 
    [ 7.500, 10.000) = 468 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     15.296 ms/op
     p(99.9900) =     21.835 ms/op
     p(99.9990) =     23.128 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.161 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.299 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.008 ms/op
Iteration   1: 3.166 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  15.351 ms/op
                 existUser·p0.9999: 20.106 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   2: 3.043 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   5.204 ms/op
                 existUser·p0.999:  8.894 ms/op
                 existUser·p0.9999: 22.347 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   3: 3.145 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   5.268 ms/op
                 existUser·p0.999:  15.039 ms/op
                 existUser·p0.9999: 23.385 ms/op
                 existUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307880
  mean =      3.117 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20070 
    [ 2.500,  5.000) = 281282 
    [ 5.000,  7.500) = 5641 
    [ 7.500, 10.000) = 472 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     14.338 ms/op
     p(99.9900) =     22.453 ms/op
     p(99.9990) =     24.314 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 7.678 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.467 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.009 ms/op
Iteration   1: 3.380 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.741 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  17.957 ms/op
                 getUser·p0.9999: 21.758 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   2: 3.314 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  15.843 ms/op
                 getUser·p0.9999: 22.359 ms/op
                 getUser·p1.00:   22.872 ms/op

Iteration   3: 3.231 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  14.486 ms/op
                 getUser·p0.9999: 21.274 ms/op
                 getUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289906
  mean =      3.307 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10821 
    [ 2.500,  5.000) = 269131 
    [ 5.000,  7.500) = 8665 
    [ 7.500, 10.000) = 764 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     22.744 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 8.631 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.191 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.013 ms/op
Iteration   1: 3.835 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  15.876 ms/op
                 listUser·p0.9999: 20.385 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   2: 3.770 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.357 ms/op
                 listUser·p0.999:  15.024 ms/op
                 listUser·p0.9999: 16.794 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   3: 3.844 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  13.071 ms/op
                 listUser·p0.9999: 16.309 ms/op
                 listUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251471
  mean =      3.816 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 96 
    [ 2.500,  5.000) = 242425 
    [ 5.000,  7.500) = 6747 
    [ 7.500, 10.000) = 1455 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.724 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     14.910 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     21.053 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.997 ± 6.609  ops/ms
ClientPb.existUser                       thrpt       3  10.229 ± 2.887  ops/ms
ClientPb.getUser                         thrpt       3  10.212 ± 3.417  ops/ms
ClientPb.listUser                        thrpt       3   8.575 ± 0.641  ops/ms
ClientPb.createUser                       avgt       3   3.166 ± 1.478   ms/op
ClientPb.existUser                        avgt       3   3.035 ± 0.997   ms/op
ClientPb.getUser                          avgt       3   3.153 ± 0.855   ms/op
ClientPb.listUser                         avgt       3   3.683 ± 0.488   ms/op
ClientPb.createUser                     sample  306383   3.128 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.260           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.600           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.300           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.296           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.835           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.968           ms/op
ClientPb.existUser                      sample  307880   3.117 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.810           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.338           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.453           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.838           ms/op
ClientPb.getUser                        sample  289906   3.307 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.935           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.662           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.824           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.007           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.053           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.872           ms/op
ClientPb.listUser                       sample  251471   3.816 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.724           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.727           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.125           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.315           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.910           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.514           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.234           ms/op
