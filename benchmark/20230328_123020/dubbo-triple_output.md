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
# Warmup Iteration   1: 2.416 ops/ms
# Warmup Iteration   2: 5.759 ops/ms
# Warmup Iteration   3: 8.925 ops/ms
Iteration   1: 9.978 ops/ms
Iteration   2: 9.988 ops/ms
Iteration   3: 10.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.068 ±(99.9%) 2.684 ops/ms [Average]
  (min, avg, max) = (9.978, 10.068, 10.238), stdev = 0.147
  CI (99.9%): [7.384, 12.752] (assumes normal distribution)


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
# Warmup Iteration   1: 3.605 ops/ms
# Warmup Iteration   2: 9.119 ops/ms
# Warmup Iteration   3: 10.154 ops/ms
Iteration   1: 10.797 ops/ms
Iteration   2: 10.108 ops/ms
Iteration   3: 10.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.439 ±(99.9%) 6.301 ops/ms [Average]
  (min, avg, max) = (10.108, 10.439, 10.797), stdev = 0.345
  CI (99.9%): [4.138, 16.740] (assumes normal distribution)


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
# Warmup Iteration   1: 3.819 ops/ms
# Warmup Iteration   2: 8.969 ops/ms
# Warmup Iteration   3: 9.515 ops/ms
Iteration   1: 9.694 ops/ms
Iteration   2: 9.970 ops/ms
Iteration   3: 10.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.945 ±(99.9%) 4.378 ops/ms [Average]
  (min, avg, max) = (9.694, 9.945, 10.172), stdev = 0.240
  CI (99.9%): [5.567, 14.323] (assumes normal distribution)


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
# Warmup Iteration   1: 3.167 ops/ms
# Warmup Iteration   2: 7.477 ops/ms
# Warmup Iteration   3: 8.322 ops/ms
Iteration   1: 8.309 ops/ms
Iteration   2: 8.579 ops/ms
Iteration   3: 8.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.564 ±(99.9%) 4.505 ops/ms [Average]
  (min, avg, max) = (8.309, 8.564, 8.802), stdev = 0.247
  CI (99.9%): [4.059, 13.068] (assumes normal distribution)


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
# Warmup Iteration   1: 7.817 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.476 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.315 ±(99.9%) 0.002 ms/op
Iteration   1: 3.110 ±(99.9%) 0.005 ms/op
Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
Iteration   3: 3.192 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.177 ±(99.9%) 1.119 ms/op [Average]
  (min, avg, max) = (3.110, 3.177, 3.230), stdev = 0.061
  CI (99.9%): [2.058, 4.296] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.314 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.377 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.004 ms/op
Iteration   1: 3.164 ±(99.9%) 0.006 ms/op
Iteration   2: 2.998 ±(99.9%) 0.003 ms/op
Iteration   3: 3.041 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.068 ±(99.9%) 1.568 ms/op [Average]
  (min, avg, max) = (2.998, 3.068, 3.164), stdev = 0.086
  CI (99.9%): [1.499, 4.636] (assumes normal distribution)


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
# Warmup Iteration   1: 8.329 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.005 ms/op
Iteration   1: 3.091 ±(99.9%) 0.005 ms/op
Iteration   2: 3.222 ±(99.9%) 0.004 ms/op
Iteration   3: 3.095 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.136 ±(99.9%) 1.353 ms/op [Average]
  (min, avg, max) = (3.091, 3.136, 3.222), stdev = 0.074
  CI (99.9%): [1.783, 4.489] (assumes normal distribution)


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
# Warmup Iteration   1: 8.891 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.005 ms/op
Iteration   1: 3.736 ±(99.9%) 0.010 ms/op
Iteration   2: 3.809 ±(99.9%) 0.006 ms/op
Iteration   3: 3.810 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.785 ±(99.9%) 0.776 ms/op [Average]
  (min, avg, max) = (3.736, 3.785, 3.810), stdev = 0.043
  CI (99.9%): [3.009, 4.561] (assumes normal distribution)


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
# Warmup Iteration   1: 9.722 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.010 ms/op
Iteration   1: 3.370 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  17.798 ms/op
                 createUser·p0.9999: 21.152 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   2: 3.239 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.798 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  21.692 ms/op
                 createUser·p0.9999: 24.864 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   3: 3.349 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.303 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.502 ms/op
                 createUser·p0.999:  17.365 ms/op
                 createUser·p0.9999: 28.669 ms/op
                 createUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289124
  mean =      3.318 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23528 
    [ 2.500,  5.000) = 259233 
    [ 5.000,  7.500) = 5499 
    [ 7.500, 10.000) = 430 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     18.313 ms/op
     p(99.9900) =     26.797 ms/op
     p(99.9990) =     29.276 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 7.333 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.349 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.008 ms/op
Iteration   1: 3.156 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  8.520 ms/op
                 existUser·p0.9999: 26.177 ms/op
                 existUser·p1.00:   27.263 ms/op

Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  8.397 ms/op
                 existUser·p0.9999: 22.010 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   3: 3.177 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.630 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  9.193 ms/op
                 existUser·p0.9999: 24.508 ms/op
                 existUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305090
  mean =      3.144 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27739 
    [ 2.500,  5.000) = 271760 
    [ 5.000,  7.500) = 5055 
    [ 7.500, 10.000) = 280 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     24.838 ms/op
     p(99.9990) =     26.629 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 8.226 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.641 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.371 ±(99.9%) 0.011 ms/op
Iteration   1: 3.324 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  17.558 ms/op
                 getUser·p0.9999: 22.708 ms/op
                 getUser·p1.00:   27.296 ms/op

Iteration   2: 3.294 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.157 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  18.820 ms/op
                 getUser·p0.9999: 38.686 ms/op
                 getUser·p1.00:   40.632 ms/op

Iteration   3: 3.219 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.945 ms/op
                 getUser·p0.999:  10.895 ms/op
                 getUser·p0.9999: 29.362 ms/op
                 getUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292523
  mean =      3.278 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 284663 
    [ 5.000, 10.000) = 7479 
    [10.000, 15.000) = 83 
    [15.000, 20.000) = 92 
    [20.000, 25.000) = 141 
    [25.000, 30.000) = 31 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     15.695 ms/op
     p(99.9900) =     37.994 ms/op
     p(99.9990) =     40.506 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


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
# Warmup Iteration   1: 9.402 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.011 ms/op
Iteration   1: 3.877 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  17.006 ms/op
                 listUser·p0.9999: 23.372 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   2: 3.807 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.837 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.847 ms/op
                 listUser·p0.999:  12.468 ms/op
                 listUser·p0.9999: 13.107 ms/op
                 listUser·p1.00:   13.189 ms/op

Iteration   3: 3.791 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  13.599 ms/op
                 listUser·p0.9999: 17.044 ms/op
                 listUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250810
  mean =      3.825 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 241305 
    [ 5.000,  7.500) = 7130 
    [ 7.500, 10.000) = 1663 
    [10.000, 12.500) = 236 
    [12.500, 15.000) = 284 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     13.615 ms/op
     p(99.9900) =     20.830 ms/op
     p(99.9990) =     24.297 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.068 ± 2.684  ops/ms
ClientPb.existUser                       thrpt       3  10.439 ± 6.301  ops/ms
ClientPb.getUser                         thrpt       3   9.945 ± 4.378  ops/ms
ClientPb.listUser                        thrpt       3   8.564 ± 4.505  ops/ms
ClientPb.createUser                       avgt       3   3.177 ± 1.119   ms/op
ClientPb.existUser                        avgt       3   3.068 ± 1.568   ms/op
ClientPb.getUser                          avgt       3   3.136 ± 1.353   ms/op
ClientPb.listUser                         avgt       3   3.785 ± 0.776   ms/op
ClientPb.createUser                     sample  289124   3.318 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.729           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.538           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.313           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.797           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.655           ms/op
ClientPb.existUser                      sample  305090   3.144 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.693           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.379           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.554           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.520           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.838           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.263           ms/op
ClientPb.getUser                        sample  292523   3.278 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.137           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.177           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.695           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.994           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.632           ms/op
ClientPb.listUser                       sample  250810   3.825 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.194           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.715           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.133           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.615           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.830           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.445           ms/op
