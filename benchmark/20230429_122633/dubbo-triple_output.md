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
# Warmup Iteration   1: 2.375 ops/ms
# Warmup Iteration   2: 5.791 ops/ms
# Warmup Iteration   3: 8.529 ops/ms
Iteration   1: 9.554 ops/ms
Iteration   2: 9.732 ops/ms
Iteration   3: 9.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.648 ±(99.9%) 1.631 ops/ms [Average]
  (min, avg, max) = (9.554, 9.648, 9.732), stdev = 0.089
  CI (99.9%): [8.016, 11.279] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.013 ops/ms
# Warmup Iteration   2: 8.816 ops/ms
# Warmup Iteration   3: 9.391 ops/ms
Iteration   1: 10.197 ops/ms
Iteration   2: 9.919 ops/ms
Iteration   3: 9.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.013 ±(99.9%) 2.913 ops/ms [Average]
  (min, avg, max) = (9.919, 10.013, 10.197), stdev = 0.160
  CI (99.9%): [7.099, 12.926] (assumes normal distribution)


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
# Warmup Iteration   1: 3.113 ops/ms
# Warmup Iteration   2: 8.509 ops/ms
# Warmup Iteration   3: 9.018 ops/ms
Iteration   1: 9.539 ops/ms
Iteration   2: 9.687 ops/ms
Iteration   3: 9.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.568 ±(99.9%) 1.959 ops/ms [Average]
  (min, avg, max) = (9.479, 9.568, 9.687), stdev = 0.107
  CI (99.9%): [7.609, 11.527] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.950 ops/ms
# Warmup Iteration   2: 7.201 ops/ms
# Warmup Iteration   3: 8.068 ops/ms
Iteration   1: 8.244 ops/ms
Iteration   2: 8.331 ops/ms
Iteration   3: 8.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.207 ±(99.9%) 2.655 ops/ms [Average]
  (min, avg, max) = (8.047, 8.207, 8.331), stdev = 0.146
  CI (99.9%): [5.552, 10.862] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.916 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.012 ms/op
Iteration   1: 3.353 ±(99.9%) 0.007 ms/op
Iteration   2: 3.490 ±(99.9%) 0.003 ms/op
Iteration   3: 3.305 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.383 ±(99.9%) 1.750 ms/op [Average]
  (min, avg, max) = (3.305, 3.383, 3.490), stdev = 0.096
  CI (99.9%): [1.633, 5.133] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.152 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.001 ms/op
Iteration   1: 3.238 ±(99.9%) 0.008 ms/op
Iteration   2: 3.236 ±(99.9%) 0.006 ms/op
Iteration   3: 3.213 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.229 ±(99.9%) 0.250 ms/op [Average]
  (min, avg, max) = (3.213, 3.229, 3.238), stdev = 0.014
  CI (99.9%): [2.979, 3.479] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.644 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.007 ms/op
Iteration   1: 3.306 ±(99.9%) 0.010 ms/op
Iteration   2: 3.454 ±(99.9%) 0.006 ms/op
Iteration   3: 3.414 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.391 ±(99.9%) 1.398 ms/op [Average]
  (min, avg, max) = (3.306, 3.391, 3.454), stdev = 0.077
  CI (99.9%): [1.993, 4.789] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 9.370 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.284 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.008 ms/op
Iteration   1: 3.914 ±(99.9%) 0.012 ms/op
Iteration   2: 4.084 ±(99.9%) 0.007 ms/op
Iteration   3: 3.945 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.981 ±(99.9%) 1.644 ms/op [Average]
  (min, avg, max) = (3.914, 3.981, 4.084), stdev = 0.090
  CI (99.9%): [2.337, 5.625] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.988 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.009 ms/op
Iteration   1: 3.290 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.401 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  19.005 ms/op
                 createUser·p0.9999: 22.652 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   2: 3.282 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   5.085 ms/op
                 createUser·p0.999:  9.427 ms/op
                 createUser·p0.9999: 23.200 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   3: 3.423 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  20.781 ms/op
                 createUser·p0.9999: 26.367 ms/op
                 createUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288084
  mean =      3.330 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9573 
    [ 2.500,  5.000) = 274297 
    [ 5.000,  7.500) = 3504 
    [ 7.500, 10.000) = 316 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     25.735 ms/op
     p(99.9990) =     27.045 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 8.484 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.009 ms/op
Iteration   1: 3.427 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  17.990 ms/op
                 existUser·p0.9999: 20.600 ms/op
                 existUser·p1.00:   21.299 ms/op

Iteration   2: 3.262 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.227 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  8.364 ms/op
                 existUser·p0.9999: 25.402 ms/op
                 existUser·p1.00:   26.444 ms/op

Iteration   3: 3.367 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  21.132 ms/op
                 existUser·p0.9999: 25.870 ms/op
                 existUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286528
  mean =      3.351 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14277 
    [ 2.500,  5.000) = 267061 
    [ 5.000,  7.500) = 4644 
    [ 7.500, 10.000) = 259 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     10.276 ms/op
     p(99.9900) =     25.439 ms/op
     p(99.9990) =     26.199 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 8.885 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.010 ms/op
Iteration   1: 3.437 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.589 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  21.134 ms/op
                 getUser·p0.9999: 27.584 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   2: 3.327 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   5.719 ms/op
                 getUser·p0.999:  19.121 ms/op
                 getUser·p0.9999: 25.362 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   3: 3.360 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.399 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  18.508 ms/op
                 getUser·p0.9999: 28.295 ms/op
                 getUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284401
  mean =      3.374 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8618 
    [ 2.500,  5.000) = 268909 
    [ 5.000,  7.500) = 5598 
    [ 7.500, 10.000) = 769 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     19.058 ms/op
     p(99.9900) =     27.773 ms/op
     p(99.9990) =     28.775 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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
# Warmup Iteration   1: 10.836 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.013 ms/op
Iteration   1: 4.010 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  21.266 ms/op
                 listUser·p0.9999: 30.641 ms/op
                 listUser·p1.00:   31.326 ms/op

Iteration   2: 4.011 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.479 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.033 ms/op
                 listUser·p0.999:  14.434 ms/op
                 listUser·p0.9999: 18.385 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   3: 4.098 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  14.942 ms/op
                 listUser·p0.9999: 17.242 ms/op
                 listUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237469
  mean =      4.039 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 228425 
    [ 5.000,  7.500) = 6449 
    [ 7.500, 10.000) = 1657 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 301 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     15.976 ms/op
     p(99.9900) =     29.254 ms/op
     p(99.9990) =     30.921 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.648 ± 1.631  ops/ms
ClientPb.existUser                       thrpt       3  10.013 ± 2.913  ops/ms
ClientPb.getUser                         thrpt       3   9.568 ± 1.959  ops/ms
ClientPb.listUser                        thrpt       3   8.207 ± 2.655  ops/ms
ClientPb.createUser                       avgt       3   3.383 ± 1.750   ms/op
ClientPb.existUser                        avgt       3   3.229 ± 0.250   ms/op
ClientPb.getUser                          avgt       3   3.391 ± 1.398   ms/op
ClientPb.listUser                         avgt       3   3.981 ± 1.644   ms/op
ClientPb.createUser                     sample  288084   3.330 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.767           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.973           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.735           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.492           ms/op
ClientPb.existUser                      sample  286528   3.351 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.227           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.276           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.439           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.444           ms/op
ClientPb.getUser                        sample  284401   3.374 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.141           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.740           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.300           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.058           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.773           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.934           ms/op
ClientPb.listUser                       sample  237469   4.039 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.284           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.976           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.254           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.326           ms/op
