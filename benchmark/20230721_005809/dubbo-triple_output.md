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
# Warmup Iteration   1: 2.239 ops/ms
# Warmup Iteration   2: 5.872 ops/ms
# Warmup Iteration   3: 8.487 ops/ms
Iteration   1: 8.944 ops/ms
Iteration   2: 8.906 ops/ms
Iteration   3: 9.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.966 ±(99.9%) 1.354 ops/ms [Average]
  (min, avg, max) = (8.906, 8.966, 9.049), stdev = 0.074
  CI (99.9%): [7.613, 10.320] (assumes normal distribution)


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
# Warmup Iteration   1: 3.348 ops/ms
# Warmup Iteration   2: 8.829 ops/ms
# Warmup Iteration   3: 9.548 ops/ms
Iteration   1: 9.490 ops/ms
Iteration   2: 9.638 ops/ms
Iteration   3: 9.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.422 ±(99.9%) 4.698 ops/ms [Average]
  (min, avg, max) = (9.137, 9.422, 9.638), stdev = 0.258
  CI (99.9%): [4.724, 14.120] (assumes normal distribution)


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
# Warmup Iteration   1: 2.969 ops/ms
# Warmup Iteration   2: 8.547 ops/ms
# Warmup Iteration   3: 9.062 ops/ms
Iteration   1: 9.170 ops/ms
Iteration   2: 9.271 ops/ms
Iteration   3: 9.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.279 ±(99.9%) 2.070 ops/ms [Average]
  (min, avg, max) = (9.170, 9.279, 9.396), stdev = 0.113
  CI (99.9%): [7.209, 11.349] (assumes normal distribution)


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
# Warmup Iteration   1: 2.896 ops/ms
# Warmup Iteration   2: 7.077 ops/ms
# Warmup Iteration   3: 7.784 ops/ms
Iteration   1: 7.812 ops/ms
Iteration   2: 7.802 ops/ms
Iteration   3: 7.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.844 ±(99.9%) 1.191 ops/ms [Average]
  (min, avg, max) = (7.802, 7.844, 7.920), stdev = 0.065
  CI (99.9%): [6.654, 9.035] (assumes normal distribution)


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
# Warmup Iteration   1: 9.092 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.006 ms/op
Iteration   1: 3.375 ±(99.9%) 0.007 ms/op
Iteration   2: 3.342 ±(99.9%) 0.011 ms/op
Iteration   3: 3.330 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.349 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (3.330, 3.349, 3.375), stdev = 0.023
  CI (99.9%): [2.926, 3.772] (assumes normal distribution)


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
# Warmup Iteration   1: 8.224 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.006 ms/op
Iteration   1: 3.192 ±(99.9%) 0.005 ms/op
Iteration   2: 3.282 ±(99.9%) 0.004 ms/op
Iteration   3: 3.229 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.234 ±(99.9%) 0.831 ms/op [Average]
  (min, avg, max) = (3.192, 3.234, 3.282), stdev = 0.046
  CI (99.9%): [2.403, 4.065] (assumes normal distribution)


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
# Warmup Iteration   1: 9.909 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.005 ms/op
Iteration   1: 3.421 ±(99.9%) 0.007 ms/op
Iteration   2: 3.406 ±(99.9%) 0.004 ms/op
Iteration   3: 3.483 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.437 ±(99.9%) 0.749 ms/op [Average]
  (min, avg, max) = (3.406, 3.437, 3.483), stdev = 0.041
  CI (99.9%): [2.687, 4.186] (assumes normal distribution)


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
# Warmup Iteration   1: 11.901 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.677 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.133 ±(99.9%) 0.007 ms/op
Iteration   1: 3.928 ±(99.9%) 0.010 ms/op
Iteration   2: 4.013 ±(99.9%) 0.012 ms/op
Iteration   3: 4.047 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.996 ±(99.9%) 1.115 ms/op [Average]
  (min, avg, max) = (3.928, 3.996, 4.047), stdev = 0.061
  CI (99.9%): [2.881, 5.111] (assumes normal distribution)


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
# Warmup Iteration   1: 8.937 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.009 ms/op
Iteration   1: 3.582 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  20.697 ms/op
                 createUser·p0.9999: 25.231 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   2: 3.479 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.436 ms/op
                 createUser·p0.999:  22.708 ms/op
                 createUser·p0.9999: 28.594 ms/op
                 createUser·p1.00:   29.458 ms/op

Iteration   3: 3.451 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.679 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  19.281 ms/op
                 createUser·p0.9999: 25.018 ms/op
                 createUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273908
  mean =      3.503 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5599 
    [ 2.500,  5.000) = 261494 
    [ 5.000,  7.500) = 5634 
    [ 7.500, 10.000) = 643 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     27.283 ms/op
     p(99.9990) =     29.377 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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
# Warmup Iteration   1: 8.636 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.008 ms/op
Iteration   1: 3.350 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  21.114 ms/op
                 existUser·p0.9999: 27.850 ms/op
                 existUser·p1.00:   29.032 ms/op

Iteration   2: 3.300 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.442 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  10.208 ms/op
                 existUser·p0.9999: 24.443 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   3: 3.300 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  15.637 ms/op
                 existUser·p0.9999: 25.503 ms/op
                 existUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289112
  mean =      3.317 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12436 
    [ 2.500,  5.000) = 271579 
    [ 5.000,  7.500) = 4232 
    [ 7.500, 10.000) = 498 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     14.744 ms/op
     p(99.9900) =     25.898 ms/op
     p(99.9990) =     28.912 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 10.922 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.001 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.009 ms/op
Iteration   1: 3.414 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.387 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  17.521 ms/op
                 getUser·p0.9999: 19.637 ms/op
                 getUser·p1.00:   21.103 ms/op

Iteration   2: 3.540 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.452 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   7.184 ms/op
                 getUser·p0.999:  20.078 ms/op
                 getUser·p0.9999: 27.033 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   3: 3.505 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.958 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  17.957 ms/op
                 getUser·p0.9999: 23.879 ms/op
                 getUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275206
  mean =      3.486 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1962 
    [ 2.500,  5.000) = 262739 
    [ 5.000,  7.500) = 9079 
    [ 7.500, 10.000) = 930 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.387 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     17.753 ms/op
     p(99.9900) =     25.394 ms/op
     p(99.9990) =     28.033 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 11.114 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.837 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.014 ms/op
Iteration   1: 3.951 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  19.431 ms/op
                 listUser·p0.9999: 22.967 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   2: 4.026 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.766 ms/op
                 listUser·p0.999:  16.493 ms/op
                 listUser·p0.9999: 19.831 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   3: 3.966 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 23.855 ms/op
                 listUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240834
  mean =      3.981 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 232638 
    [ 5.000,  7.500) = 6048 
    [ 7.500, 10.000) = 1373 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     16.193 ms/op
     p(99.9900) =     22.443 ms/op
     p(99.9990) =     24.305 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.966 ± 1.354  ops/ms
ClientPb.existUser                       thrpt       3   9.422 ± 4.698  ops/ms
ClientPb.getUser                         thrpt       3   9.279 ± 2.070  ops/ms
ClientPb.listUser                        thrpt       3   7.844 ± 1.191  ops/ms
ClientPb.createUser                       avgt       3   3.349 ± 0.423   ms/op
ClientPb.existUser                        avgt       3   3.234 ± 0.831   ms/op
ClientPb.getUser                          avgt       3   3.437 ± 0.749   ms/op
ClientPb.listUser                         avgt       3   3.996 ± 1.115   ms/op
ClientPb.createUser                     sample  273908   3.503 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.354           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.396           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.972           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.464           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.283           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.458           ms/op
ClientPb.existUser                      sample  289112   3.317 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.260           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.898           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.744           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.898           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.032           ms/op
ClientPb.getUser                        sample  275206   3.486 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.387           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.190           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.922           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.753           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.394           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.082           ms/op
ClientPb.listUser                       sample  240834   3.981 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.745           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.193           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.443           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.609           ms/op
