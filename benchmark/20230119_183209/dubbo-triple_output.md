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
# Warmup Iteration   1: 2.542 ops/ms
# Warmup Iteration   2: 5.987 ops/ms
# Warmup Iteration   3: 8.873 ops/ms
Iteration   1: 9.877 ops/ms
Iteration   2: 10.112 ops/ms
Iteration   3: 9.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.930 ±(99.9%) 2.950 ops/ms [Average]
  (min, avg, max) = (9.802, 9.930, 10.112), stdev = 0.162
  CI (99.9%): [6.981, 12.880] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.922 ops/ms
# Warmup Iteration   2: 9.276 ops/ms
# Warmup Iteration   3: 9.970 ops/ms
Iteration   1: 10.457 ops/ms
Iteration   2: 10.312 ops/ms
Iteration   3: 10.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.485 ±(99.9%) 3.429 ops/ms [Average]
  (min, avg, max) = (10.312, 10.485, 10.685), stdev = 0.188
  CI (99.9%): [7.056, 13.914] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.300 ops/ms
# Warmup Iteration   2: 8.877 ops/ms
# Warmup Iteration   3: 9.841 ops/ms
Iteration   1: 10.123 ops/ms
Iteration   2: 10.144 ops/ms
Iteration   3: 10.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.144 ±(99.9%) 0.393 ops/ms [Average]
  (min, avg, max) = (10.123, 10.144, 10.166), stdev = 0.022
  CI (99.9%): [9.752, 10.537] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.522 ops/ms
# Warmup Iteration   2: 7.990 ops/ms
# Warmup Iteration   3: 8.337 ops/ms
Iteration   1: 8.492 ops/ms
Iteration   2: 8.299 ops/ms
Iteration   3: 8.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.292 ±(99.9%) 3.722 ops/ms [Average]
  (min, avg, max) = (8.085, 8.292, 8.492), stdev = 0.204
  CI (99.9%): [4.570, 12.013] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.669 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.002 ms/op
Iteration   1: 3.190 ±(99.9%) 0.008 ms/op
Iteration   2: 3.124 ±(99.9%) 0.008 ms/op
Iteration   3: 3.283 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.199 ±(99.9%) 1.456 ms/op [Average]
  (min, avg, max) = (3.124, 3.199, 3.283), stdev = 0.080
  CI (99.9%): [1.743, 4.655] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.516 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.342 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.005 ms/op
Iteration   1: 3.070 ±(99.9%) 0.005 ms/op
Iteration   2: 3.100 ±(99.9%) 0.003 ms/op
Iteration   3: 2.980 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.050 ±(99.9%) 1.142 ms/op [Average]
  (min, avg, max) = (2.980, 3.050, 3.100), stdev = 0.063
  CI (99.9%): [1.908, 4.192] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.287 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.416 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.002 ms/op
Iteration   1: 3.165 ±(99.9%) 0.002 ms/op
Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
Iteration   3: 3.131 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.130 ±(99.9%) 0.633 ms/op [Average]
  (min, avg, max) = (3.095, 3.130, 3.165), stdev = 0.035
  CI (99.9%): [2.498, 3.763] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.313 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.006 ms/op
Iteration   1: 3.688 ±(99.9%) 0.009 ms/op
Iteration   2: 3.702 ±(99.9%) 0.010 ms/op
Iteration   3: 3.680 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.690 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (3.680, 3.690, 3.702), stdev = 0.011
  CI (99.9%): [3.485, 3.895] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.003 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.010 ms/op
Iteration   1: 3.194 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  10.186 ms/op
                 createUser·p0.9999: 20.972 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   2: 3.183 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  17.603 ms/op
                 createUser·p0.9999: 21.889 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   3: 3.269 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.382 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  14.130 ms/op
                 createUser·p0.9999: 21.535 ms/op
                 createUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298553
  mean =      3.215 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19972 
    [ 2.500,  5.000) = 272071 
    [ 5.000,  7.500) = 5471 
    [ 7.500, 10.000) = 564 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     14.174 ms/op
     p(99.9900) =     21.501 ms/op
     p(99.9990) =     24.709 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.559 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.008 ms/op
Iteration   1: 3.145 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.184 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  10.027 ms/op
                 existUser·p0.9999: 25.379 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   2: 3.040 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  14.283 ms/op
                 existUser·p0.9999: 21.774 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.526 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  7.938 ms/op
                 existUser·p0.9999: 19.104 ms/op
                 existUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310748
  mean =      3.086 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20815 
    [ 2.500,  5.000) = 284318 
    [ 5.000,  7.500) = 4955 
    [ 7.500, 10.000) = 271 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     13.591 ms/op
     p(99.9900) =     24.606 ms/op
     p(99.9990) =     25.814 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.882 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.010 ms/op
Iteration   1: 3.237 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.292 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.802 ms/op
                 getUser·p0.999:  15.172 ms/op
                 getUser·p0.9999: 28.610 ms/op
                 getUser·p1.00:   29.655 ms/op

Iteration   2: 3.260 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  15.171 ms/op
                 getUser·p0.9999: 24.451 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   3: 3.270 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.814 ms/op
                 getUser·p0.999:  12.210 ms/op
                 getUser·p0.9999: 20.552 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294719
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13967 
    [ 2.500,  5.000) = 271547 
    [ 5.000,  7.500) = 8053 
    [ 7.500, 10.000) = 695 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     29.434 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.573 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.012 ms/op
Iteration   1: 3.764 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.936 ms/op
                 listUser·p0.999:  15.024 ms/op
                 listUser·p0.9999: 21.266 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   2: 3.756 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.733 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  12.822 ms/op
                 listUser·p0.9999: 14.613 ms/op
                 listUser·p1.00:   15.450 ms/op

Iteration   3: 3.782 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  13.059 ms/op
                 listUser·p0.9999: 17.564 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254541
  mean =      3.767 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 247960 
    [ 5.000,  7.500) = 4660 
    [ 7.500, 10.000) = 1235 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 233 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     13.679 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     21.758 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.930 ± 2.950  ops/ms
ClientPb.existUser                       thrpt       3  10.485 ± 3.429  ops/ms
ClientPb.getUser                         thrpt       3  10.144 ± 0.393  ops/ms
ClientPb.listUser                        thrpt       3   8.292 ± 3.722  ops/ms
ClientPb.createUser                       avgt       3   3.199 ± 1.456   ms/op
ClientPb.existUser                        avgt       3   3.050 ± 1.142   ms/op
ClientPb.getUser                          avgt       3   3.130 ± 0.633   ms/op
ClientPb.listUser                         avgt       3   3.690 ± 0.205   ms/op
ClientPb.createUser                     sample  298553   3.215 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.137           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.580           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.080           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.174           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.501           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.395           ms/op
ClientPb.existUser                      sample  310748   3.086 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.133           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.591           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.606           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.018           ms/op
ClientPb.getUser                        sample  294719   3.256 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.155           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.375           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.038           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.122           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.460           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.655           ms/op
ClientPb.listUser                       sample  254541   3.767 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.126           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.012           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.679           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.004           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.758           ms/op
