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
# Warmup Iteration   1: 1.333 ops/ms
# Warmup Iteration   2: 3.938 ops/ms
# Warmup Iteration   3: 5.950 ops/ms
Iteration   1: 6.374 ops/ms
Iteration   2: 6.468 ops/ms
Iteration   3: 6.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.489 ±(99.9%) 2.303 ops/ms [Average]
  (min, avg, max) = (6.374, 6.489, 6.624), stdev = 0.126
  CI (99.9%): [4.186, 8.791] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.958 ops/ms
# Warmup Iteration   2: 6.072 ops/ms
# Warmup Iteration   3: 6.926 ops/ms
Iteration   1: 7.344 ops/ms
Iteration   2: 7.335 ops/ms
Iteration   3: 7.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.374 ±(99.9%) 1.088 ops/ms [Average]
  (min, avg, max) = (7.335, 7.374, 7.443), stdev = 0.060
  CI (99.9%): [6.286, 8.462] (assumes normal distribution)


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
# Warmup Iteration   1: 1.868 ops/ms
# Warmup Iteration   2: 5.669 ops/ms
# Warmup Iteration   3: 6.464 ops/ms
Iteration   1: 6.572 ops/ms
Iteration   2: 6.630 ops/ms
Iteration   3: 6.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.622 ±(99.9%) 0.834 ops/ms [Average]
  (min, avg, max) = (6.572, 6.622, 6.662), stdev = 0.046
  CI (99.9%): [5.788, 7.455] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.754 ops/ms
# Warmup Iteration   2: 4.903 ops/ms
# Warmup Iteration   3: 5.829 ops/ms
Iteration   1: 5.911 ops/ms
Iteration   2: 5.778 ops/ms
Iteration   3: 5.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.880 ±(99.9%) 1.663 ops/ms [Average]
  (min, avg, max) = (5.778, 5.880, 5.952), stdev = 0.091
  CI (99.9%): [4.217, 7.544] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 16.928 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.717 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.958 ±(99.9%) 0.016 ms/op
Iteration   1: 4.981 ±(99.9%) 0.008 ms/op
Iteration   2: 4.646 ±(99.9%) 0.012 ms/op
Iteration   3: 4.810 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.812 ±(99.9%) 3.054 ms/op [Average]
  (min, avg, max) = (4.646, 4.812, 4.981), stdev = 0.167
  CI (99.9%): [1.758, 7.866] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 14.110 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.013 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.681 ±(99.9%) 0.007 ms/op
Iteration   1: 4.524 ±(99.9%) 0.011 ms/op
Iteration   2: 4.610 ±(99.9%) 0.008 ms/op
Iteration   3: 4.601 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.578 ±(99.9%) 0.865 ms/op [Average]
  (min, avg, max) = (4.524, 4.578, 4.610), stdev = 0.047
  CI (99.9%): [3.713, 5.443] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 15.441 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.483 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.938 ±(99.9%) 0.009 ms/op
Iteration   1: 4.699 ±(99.9%) 0.016 ms/op
Iteration   2: 4.769 ±(99.9%) 0.014 ms/op
Iteration   3: 4.905 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.791 ±(99.9%) 1.913 ms/op [Average]
  (min, avg, max) = (4.699, 4.791, 4.905), stdev = 0.105
  CI (99.9%): [2.878, 6.703] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 17.209 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.669 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.008 ±(99.9%) 0.014 ms/op
Iteration   1: 5.373 ±(99.9%) 0.018 ms/op
Iteration   2: 5.292 ±(99.9%) 0.018 ms/op
Iteration   3: 5.423 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.363 ±(99.9%) 1.209 ms/op [Average]
  (min, avg, max) = (5.292, 5.363, 5.423), stdev = 0.066
  CI (99.9%): [4.154, 6.572] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.515 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 5.707 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.229 ±(99.9%) 0.022 ms/op
Iteration   1: 4.802 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.095 ms/op
                 createUser·p0.50:   4.612 ms/op
                 createUser·p0.90:   5.744 ms/op
                 createUser·p0.95:   6.259 ms/op
                 createUser·p0.99:   9.355 ms/op
                 createUser·p0.999:  21.463 ms/op
                 createUser·p0.9999: 24.620 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   2: 4.798 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.208 ms/op
                 createUser·p0.50:   4.620 ms/op
                 createUser·p0.90:   5.702 ms/op
                 createUser·p0.95:   6.390 ms/op
                 createUser·p0.99:   8.368 ms/op
                 createUser·p0.999:  16.216 ms/op
                 createUser·p0.9999: 29.710 ms/op
                 createUser·p1.00:   30.900 ms/op

Iteration   3: 4.738 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   4.547 ms/op
                 createUser·p0.90:   5.571 ms/op
                 createUser·p0.95:   6.062 ms/op
                 createUser·p0.99:   8.479 ms/op
                 createUser·p0.999:  25.541 ms/op
                 createUser·p0.9999: 28.721 ms/op
                 createUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 200891
  mean =      4.779 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 98 
    [ 2.500,  5.000) = 145432 
    [ 5.000,  7.500) = 51586 
    [ 7.500, 10.000) = 2651 
    [10.000, 12.500) = 560 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.669 ms/op
     p(95.0000) =      6.234 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     22.653 ms/op
     p(99.9900) =     28.604 ms/op
     p(99.9990) =     30.867 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.540 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 5.186 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.574 ±(99.9%) 0.015 ms/op
Iteration   1: 4.474 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.122 ms/op
                 existUser·p0.50:   4.309 ms/op
                 existUser·p0.90:   5.251 ms/op
                 existUser·p0.95:   5.931 ms/op
                 existUser·p0.99:   8.217 ms/op
                 existUser·p0.999:  12.911 ms/op
                 existUser·p0.9999: 23.167 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   2: 4.626 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.142 ms/op
                 existUser·p0.50:   4.391 ms/op
                 existUser·p0.90:   5.685 ms/op
                 existUser·p0.95:   6.324 ms/op
                 existUser·p0.99:   8.438 ms/op
                 existUser·p0.999:  17.155 ms/op
                 existUser·p0.9999: 25.377 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   3: 4.530 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.757 ms/op
                 existUser·p0.50:   4.334 ms/op
                 existUser·p0.90:   5.308 ms/op
                 existUser·p0.95:   5.849 ms/op
                 existUser·p0.99:   8.266 ms/op
                 existUser·p0.999:  26.149 ms/op
                 existUser·p0.9999: 28.407 ms/op
                 existUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 211247
  mean =      4.543 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 174139 
    [ 5.000,  7.500) = 33565 
    [ 7.500, 10.000) = 2693 
    [10.000, 12.500) = 406 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.757 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      8.336 ms/op
     p(99.9000) =     21.029 ms/op
     p(99.9900) =     27.652 ms/op
     p(99.9990) =     31.228 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.400 ±(99.9%) 0.213 ms/op
# Warmup Iteration   2: 5.243 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.810 ±(99.9%) 0.014 ms/op
Iteration   1: 4.717 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.868 ms/op
                 getUser·p0.50:   4.481 ms/op
                 getUser·p0.90:   5.710 ms/op
                 getUser·p0.95:   6.423 ms/op
                 getUser·p0.99:   9.159 ms/op
                 getUser·p0.999:  14.893 ms/op
                 getUser·p0.9999: 28.227 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   2: 4.893 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.925 ms/op
                 getUser·p0.50:   4.628 ms/op
                 getUser·p0.90:   5.775 ms/op
                 getUser·p0.95:   7.217 ms/op
                 getUser·p0.99:   9.748 ms/op
                 getUser·p0.999:  23.800 ms/op
                 getUser·p0.9999: 26.736 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   3: 4.707 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.257 ms/op
                 getUser·p0.50:   4.506 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   6.169 ms/op
                 getUser·p0.99:   8.373 ms/op
                 getUser·p0.999:  21.726 ms/op
                 getUser·p0.9999: 31.339 ms/op
                 getUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 201173
  mean =      4.771 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 151503 
    [ 5.000,  7.500) = 44032 
    [ 7.500, 10.000) = 4323 
    [10.000, 12.500) = 760 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.868 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.661 ms/op
     p(95.0000) =      6.480 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     21.692 ms/op
     p(99.9900) =     30.299 ms/op
     p(99.9990) =     31.489 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.827 ±(99.9%) 0.224 ms/op
# Warmup Iteration   2: 5.932 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.525 ±(99.9%) 0.021 ms/op
Iteration   1: 5.427 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.576 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   6.906 ms/op
                 listUser·p0.99:   9.404 ms/op
                 listUser·p0.999:  23.341 ms/op
                 listUser·p0.9999: 26.746 ms/op
                 listUser·p1.00:   27.361 ms/op

Iteration   2: 5.454 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.515 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   6.316 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   10.372 ms/op
                 listUser·p0.999:  22.263 ms/op
                 listUser·p0.9999: 27.665 ms/op
                 listUser·p1.00:   28.574 ms/op

Iteration   3: 5.394 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   5.104 ms/op
                 listUser·p0.90:   6.488 ms/op
                 listUser·p0.95:   7.234 ms/op
                 listUser·p0.99:   10.912 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 27.689 ms/op
                 listUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 176759
  mean =      5.425 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 66215 
    [ 5.000,  7.500) = 104153 
    [ 7.500, 10.000) = 4492 
    [10.000, 12.500) = 1185 
    [12.500, 15.000) = 304 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      2.175 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.373 ms/op
     p(95.0000) =      7.029 ms/op
     p(99.0000) =     10.240 ms/op
     p(99.9000) =     22.003 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     28.297 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.489 ± 2.303  ops/ms
ClientPb.existUser                       thrpt       3   7.374 ± 1.088  ops/ms
ClientPb.getUser                         thrpt       3   6.622 ± 0.834  ops/ms
ClientPb.listUser                        thrpt       3   5.880 ± 1.663  ops/ms
ClientPb.createUser                       avgt       3   4.812 ± 3.054   ms/op
ClientPb.existUser                        avgt       3   4.578 ± 0.865   ms/op
ClientPb.getUser                          avgt       3   4.791 ± 1.913   ms/op
ClientPb.listUser                         avgt       3   5.363 ± 1.209   ms/op
ClientPb.createUser                     sample  200891   4.779 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.943           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.596           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.669           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.234           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.667           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.653           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.604           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.900           ms/op
ClientPb.existUser                      sample  211247   4.543 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.757           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.046           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.336           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.029           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.652           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.523           ms/op
ClientPb.getUser                        sample  201173   4.771 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.868           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.538           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.661           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.480           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.175           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.692           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.299           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.490           ms/op
ClientPb.listUser                       sample  176759   5.425 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.175           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.194           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.373           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.029           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.240           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.003           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.623           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.574           ms/op
