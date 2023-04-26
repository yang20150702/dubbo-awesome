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
# Warmup Iteration   1: 2.353 ops/ms
# Warmup Iteration   2: 5.913 ops/ms
# Warmup Iteration   3: 8.551 ops/ms
Iteration   1: 9.023 ops/ms
Iteration   2: 9.218 ops/ms
Iteration   3: 9.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.223 ±(99.9%) 3.715 ops/ms [Average]
  (min, avg, max) = (9.023, 9.223, 9.430), stdev = 0.204
  CI (99.9%): [5.509, 12.938] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.091 ops/ms
# Warmup Iteration   2: 8.931 ops/ms
# Warmup Iteration   3: 9.818 ops/ms
Iteration   1: 9.581 ops/ms
Iteration   2: 9.651 ops/ms
Iteration   3: 9.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.721 ±(99.9%) 3.382 ops/ms [Average]
  (min, avg, max) = (9.581, 9.721, 9.932), stdev = 0.185
  CI (99.9%): [6.340, 13.103] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.462 ops/ms
# Warmup Iteration   2: 8.340 ops/ms
# Warmup Iteration   3: 9.211 ops/ms
Iteration   1: 9.490 ops/ms
Iteration   2: 9.637 ops/ms
Iteration   3: 9.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.633 ±(99.9%) 2.562 ops/ms [Average]
  (min, avg, max) = (9.490, 9.633, 9.770), stdev = 0.140
  CI (99.9%): [7.071, 12.194] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.909 ops/ms
# Warmup Iteration   2: 7.319 ops/ms
# Warmup Iteration   3: 7.913 ops/ms
Iteration   1: 8.003 ops/ms
Iteration   2: 8.221 ops/ms
Iteration   3: 8.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.112 ±(99.9%) 1.991 ops/ms [Average]
  (min, avg, max) = (8.003, 8.112, 8.221), stdev = 0.109
  CI (99.9%): [6.121, 10.103] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.656 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.008 ms/op
Iteration   1: 3.517 ±(99.9%) 0.004 ms/op
Iteration   2: 3.479 ±(99.9%) 0.005 ms/op
Iteration   3: 3.366 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.454 ±(99.9%) 1.432 ms/op [Average]
  (min, avg, max) = (3.366, 3.454, 3.517), stdev = 0.079
  CI (99.9%): [2.022, 4.886] (assumes normal distribution)


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
# Warmup Iteration   1: 8.843 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.005 ms/op
Iteration   1: 3.177 ±(99.9%) 0.006 ms/op
Iteration   2: 3.108 ±(99.9%) 0.009 ms/op
Iteration   3: 3.219 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.168 ±(99.9%) 1.026 ms/op [Average]
  (min, avg, max) = (3.108, 3.168, 3.219), stdev = 0.056
  CI (99.9%): [2.142, 4.194] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.503 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.818 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.579 ±(99.9%) 0.005 ms/op
Iteration   1: 3.399 ±(99.9%) 0.011 ms/op
Iteration   2: 3.419 ±(99.9%) 0.005 ms/op
Iteration   3: 3.383 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.400 ±(99.9%) 0.331 ms/op [Average]
  (min, avg, max) = (3.383, 3.400, 3.419), stdev = 0.018
  CI (99.9%): [3.069, 3.731] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.839 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.008 ms/op
Iteration   1: 3.833 ±(99.9%) 0.012 ms/op
Iteration   2: 3.935 ±(99.9%) 0.010 ms/op
Iteration   3: 3.716 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.828 ±(99.9%) 1.999 ms/op [Average]
  (min, avg, max) = (3.716, 3.828, 3.935), stdev = 0.110
  CI (99.9%): [1.828, 5.827] (assumes normal distribution)


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
# Warmup Iteration   1: 8.561 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.249 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.011 ms/op
Iteration   1: 3.412 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  20.353 ms/op
                 createUser·p0.9999: 23.608 ms/op
                 createUser·p1.00:   26.018 ms/op

Iteration   2: 3.419 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.518 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  22.182 ms/op
                 createUser·p0.9999: 27.645 ms/op
                 createUser·p1.00:   28.869 ms/op

Iteration   3: 3.391 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  17.084 ms/op
                 createUser·p0.9999: 24.425 ms/op
                 createUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281726
  mean =      3.407 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11181 
    [ 2.500,  5.000) = 264541 
    [ 5.000,  7.500) = 4981 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     26.721 ms/op
     p(99.9990) =     28.735 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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
# Warmup Iteration   1: 9.454 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.601 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.009 ms/op
Iteration   1: 3.344 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.210 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  18.523 ms/op
                 existUser·p0.9999: 27.368 ms/op
                 existUser·p1.00:   29.852 ms/op

Iteration   2: 3.254 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.572 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  9.859 ms/op
                 existUser·p0.9999: 23.664 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   3: 3.352 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.466 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  12.321 ms/op
                 existUser·p0.9999: 34.305 ms/op
                 existUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289400
  mean =      3.316 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14856 
    [ 2.500,  5.000) = 268390 
    [ 5.000,  7.500) = 5217 
    [ 7.500, 10.000) = 513 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     12.272 ms/op
     p(99.9900) =     32.180 ms/op
     p(99.9990) =     34.879 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.695 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.982 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.012 ms/op
Iteration   1: 3.487 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  20.323 ms/op
                 getUser·p0.9999: 24.662 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   2: 3.529 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.477 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  23.063 ms/op
                 getUser·p0.9999: 25.459 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   3: 3.461 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.968 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  22.282 ms/op
                 getUser·p0.9999: 31.588 ms/op
                 getUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274871
  mean =      3.492 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2819 
    [ 2.500,  5.000) = 263540 
    [ 5.000,  7.500) = 6855 
    [ 7.500, 10.000) = 1100 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 151 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     21.377 ms/op
     p(99.9900) =     30.622 ms/op
     p(99.9990) =     31.687 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 9.973 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.534 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.013 ms/op
Iteration   1: 4.042 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  18.579 ms/op
                 listUser·p0.9999: 22.088 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 3.981 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.792 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 18.285 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   3: 4.087 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 19.410 ms/op
                 listUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237782
  mean =      4.036 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 229741 
    [ 5.000,  7.500) = 5198 
    [ 7.500, 10.000) = 1996 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 270 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     15.761 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.223 ± 3.715  ops/ms
ClientPb.existUser                       thrpt       3   9.721 ± 3.382  ops/ms
ClientPb.getUser                         thrpt       3   9.633 ± 2.562  ops/ms
ClientPb.listUser                        thrpt       3   8.112 ± 1.991  ops/ms
ClientPb.createUser                       avgt       3   3.454 ± 1.432   ms/op
ClientPb.existUser                        avgt       3   3.168 ± 1.026   ms/op
ClientPb.getUser                          avgt       3   3.400 ± 0.331   ms/op
ClientPb.listUser                         avgt       3   3.828 ± 1.999   ms/op
ClientPb.createUser                     sample  281726   3.407 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.141           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.743           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.121           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.721           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.869           ms/op
ClientPb.existUser                      sample  289400   3.316 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.572           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.808           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.272           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.180           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.193           ms/op
ClientPb.getUser                        sample  274871   3.492 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.376           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.849           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.377           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.622           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.687           ms/op
ClientPb.listUser                       sample  237782   4.036 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.341           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.815           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.761           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.627           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.512           ms/op
