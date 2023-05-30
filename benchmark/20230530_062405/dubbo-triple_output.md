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
# Warmup Iteration   1: 2.357 ops/ms
# Warmup Iteration   2: 5.839 ops/ms
# Warmup Iteration   3: 9.241 ops/ms
Iteration   1: 10.155 ops/ms
Iteration   2: 9.679 ops/ms
Iteration   3: 9.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.876 ±(99.9%) 4.536 ops/ms [Average]
  (min, avg, max) = (9.679, 9.876, 10.155), stdev = 0.249
  CI (99.9%): [5.340, 14.411] (assumes normal distribution)


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
# Warmup Iteration   1: 3.554 ops/ms
# Warmup Iteration   2: 8.658 ops/ms
# Warmup Iteration   3: 10.087 ops/ms
Iteration   1: 10.401 ops/ms
Iteration   2: 10.259 ops/ms
Iteration   3: 10.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.238 ±(99.9%) 3.188 ops/ms [Average]
  (min, avg, max) = (10.054, 10.238, 10.401), stdev = 0.175
  CI (99.9%): [7.050, 13.427] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.514 ops/ms
# Warmup Iteration   2: 8.251 ops/ms
# Warmup Iteration   3: 9.375 ops/ms
Iteration   1: 9.874 ops/ms
Iteration   2: 10.074 ops/ms
Iteration   3: 9.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.900 ±(99.9%) 2.964 ops/ms [Average]
  (min, avg, max) = (9.752, 9.900, 10.074), stdev = 0.162
  CI (99.9%): [6.936, 12.864] (assumes normal distribution)


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
# Warmup Iteration   1: 3.419 ops/ms
# Warmup Iteration   2: 7.627 ops/ms
# Warmup Iteration   3: 8.378 ops/ms
Iteration   1: 8.485 ops/ms
Iteration   2: 8.450 ops/ms
Iteration   3: 8.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.562 ±(99.9%) 3.018 ops/ms [Average]
  (min, avg, max) = (8.450, 8.562, 8.752), stdev = 0.165
  CI (99.9%): [5.544, 11.581] (assumes normal distribution)


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
# Warmup Iteration   1: 7.397 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.468 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.008 ms/op
Iteration   1: 3.188 ±(99.9%) 0.008 ms/op
Iteration   2: 3.313 ±(99.9%) 0.007 ms/op
Iteration   3: 3.254 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.252 ±(99.9%) 1.141 ms/op [Average]
  (min, avg, max) = (3.188, 3.252, 3.313), stdev = 0.063
  CI (99.9%): [2.111, 4.392] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.009 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.002 ms/op
Iteration   1: 3.037 ±(99.9%) 0.005 ms/op
Iteration   2: 3.039 ±(99.9%) 0.008 ms/op
Iteration   3: 3.074 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.050 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (3.037, 3.050, 3.074), stdev = 0.021
  CI (99.9%): [2.675, 3.425] (assumes normal distribution)


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
# Warmup Iteration   1: 8.662 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.434 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.002 ms/op
Iteration   1: 3.304 ±(99.9%) 0.002 ms/op
Iteration   2: 3.314 ±(99.9%) 0.010 ms/op
Iteration   3: 3.259 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.292 ±(99.9%) 0.541 ms/op [Average]
  (min, avg, max) = (3.259, 3.292, 3.314), stdev = 0.030
  CI (99.9%): [2.751, 3.834] (assumes normal distribution)


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
# Warmup Iteration   1: 9.209 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.039 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.007 ms/op
Iteration   1: 3.703 ±(99.9%) 0.012 ms/op
Iteration   2: 3.754 ±(99.9%) 0.009 ms/op
Iteration   3: 3.682 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.713 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (3.682, 3.713, 3.754), stdev = 0.037
  CI (99.9%): [3.031, 4.394] (assumes normal distribution)


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
# Warmup Iteration   1: 8.969 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.010 ms/op
Iteration   1: 3.222 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  9.191 ms/op
                 createUser·p0.9999: 20.414 ms/op
                 createUser·p1.00:   21.463 ms/op

Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.751 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  11.198 ms/op
                 createUser·p0.9999: 22.971 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   3: 3.181 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  16.695 ms/op
                 createUser·p0.9999: 27.492 ms/op
                 createUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299359
  mean =      3.202 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12236 
    [ 2.500,  5.000) = 283026 
    [ 5.000,  7.500) = 3306 
    [ 7.500, 10.000) = 417 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.038 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     16.679 ms/op
     p(99.9900) =     26.380 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 7.635 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.367 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.008 ms/op
Iteration   1: 3.046 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.252 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  17.794 ms/op
                 existUser·p0.9999: 20.874 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 3.074 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  12.910 ms/op
                 existUser·p0.9999: 21.941 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   3: 3.193 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  14.795 ms/op
                 existUser·p0.9999: 20.839 ms/op
                 existUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309257
  mean =      3.103 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21742 
    [ 2.500,  5.000) = 283288 
    [ 5.000,  7.500) = 3260 
    [ 7.500, 10.000) = 348 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     14.791 ms/op
     p(99.9900) =     21.138 ms/op
     p(99.9990) =     22.704 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 8.015 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.542 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.011 ms/op
Iteration   1: 3.241 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.546 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  10.479 ms/op
                 getUser·p0.9999: 21.906 ms/op
                 getUser·p1.00:   22.184 ms/op

Iteration   2: 3.199 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.364 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.962 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  10.847 ms/op
                 getUser·p0.9999: 27.623 ms/op
                 getUser·p1.00:   29.524 ms/op

Iteration   3: 3.194 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  15.694 ms/op
                 getUser·p0.9999: 25.263 ms/op
                 getUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298679
  mean =      3.211 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8567 
    [ 2.500,  5.000) = 282298 
    [ 5.000,  7.500) = 6903 
    [ 7.500, 10.000) = 536 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     15.406 ms/op
     p(99.9900) =     25.908 ms/op
     p(99.9990) =     27.970 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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
# Warmup Iteration   1: 9.703 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.319 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.011 ms/op
Iteration   1: 3.732 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.880 ms/op
                 listUser·p0.999:  14.657 ms/op
                 listUser·p0.9999: 26.425 ms/op
                 listUser·p1.00:   27.623 ms/op

Iteration   2: 3.773 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  14.402 ms/op
                 listUser·p0.9999: 17.636 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 3.814 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.602 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 24.006 ms/op
                 listUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254255
  mean =      3.773 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 247768 
    [ 5.000,  7.500) = 4678 
    [ 7.500, 10.000) = 982 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 315 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     15.417 ms/op
     p(99.9900) =     24.553 ms/op
     p(99.9990) =     27.490 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.876 ± 4.536  ops/ms
ClientPb.existUser                       thrpt       3  10.238 ± 3.188  ops/ms
ClientPb.getUser                         thrpt       3   9.900 ± 2.964  ops/ms
ClientPb.listUser                        thrpt       3   8.562 ± 3.018  ops/ms
ClientPb.createUser                       avgt       3   3.252 ± 1.141   ms/op
ClientPb.existUser                        avgt       3   3.050 ± 0.375   ms/op
ClientPb.getUser                          avgt       3   3.292 ± 0.541   ms/op
ClientPb.listUser                         avgt       3   3.713 ± 0.682   ms/op
ClientPb.createUser                     sample  299359   3.202 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.038           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.576           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.679           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.380           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.475           ms/op
ClientPb.existUser                      sample  309257   3.103 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.190           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.374           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.791           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.138           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.396           ms/op
ClientPb.getUser                        sample  298679   3.211 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.237           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.980           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.406           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.908           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.524           ms/op
ClientPb.listUser                       sample  254255   3.773 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.464           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.849           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.417           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.553           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.623           ms/op
