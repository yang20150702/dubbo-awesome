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
# Warmup Iteration   1: 2.713 ops/ms
# Warmup Iteration   2: 6.843 ops/ms
# Warmup Iteration   3: 9.534 ops/ms
Iteration   1: 9.317 ops/ms
Iteration   2: 9.902 ops/ms
Iteration   3: 9.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.634 ±(99.9%) 5.394 ops/ms [Average]
  (min, avg, max) = (9.317, 9.634, 9.902), stdev = 0.296
  CI (99.9%): [4.239, 15.028] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.659 ops/ms
# Warmup Iteration   2: 9.902 ops/ms
# Warmup Iteration   3: 10.246 ops/ms
Iteration   1: 10.282 ops/ms
Iteration   2: 10.197 ops/ms
Iteration   3: 10.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.349 ±(99.9%) 3.555 ops/ms [Average]
  (min, avg, max) = (10.197, 10.349, 10.569), stdev = 0.195
  CI (99.9%): [6.794, 13.905] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.729 ops/ms
# Warmup Iteration   2: 9.314 ops/ms
# Warmup Iteration   3: 10.037 ops/ms
Iteration   1: 10.223 ops/ms
Iteration   2: 10.158 ops/ms
Iteration   3: 10.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.313 ±(99.9%) 3.914 ops/ms [Average]
  (min, avg, max) = (10.158, 10.313, 10.558), stdev = 0.215
  CI (99.9%): [6.399, 14.227] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.266 ops/ms
# Warmup Iteration   2: 7.800 ops/ms
# Warmup Iteration   3: 8.618 ops/ms
Iteration   1: 8.923 ops/ms
Iteration   2: 8.590 ops/ms
Iteration   3: 8.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.760 ±(99.9%) 3.036 ops/ms [Average]
  (min, avg, max) = (8.590, 8.760, 8.923), stdev = 0.166
  CI (99.9%): [5.723, 11.796] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.799 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.417 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.004 ms/op
Iteration   1: 3.165 ±(99.9%) 0.006 ms/op
Iteration   2: 3.155 ±(99.9%) 0.006 ms/op
Iteration   3: 3.158 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.159 ±(99.9%) 0.089 ms/op [Average]
  (min, avg, max) = (3.155, 3.159, 3.165), stdev = 0.005
  CI (99.9%): [3.070, 3.248] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 6.608 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.002 ms/op
Iteration   1: 2.966 ±(99.9%) 0.003 ms/op
Iteration   2: 3.017 ±(99.9%) 0.002 ms/op
Iteration   3: 3.139 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.041 ±(99.9%) 1.624 ms/op [Average]
  (min, avg, max) = (2.966, 3.041, 3.139), stdev = 0.089
  CI (99.9%): [1.417, 4.665] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 6.714 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.006 ms/op
Iteration   1: 3.169 ±(99.9%) 0.005 ms/op
Iteration   2: 3.211 ±(99.9%) 0.005 ms/op
Iteration   3: 3.041 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.140 ±(99.9%) 1.610 ms/op [Average]
  (min, avg, max) = (3.041, 3.140, 3.211), stdev = 0.088
  CI (99.9%): [1.530, 4.751] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.594 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.007 ms/op
Iteration   1: 3.620 ±(99.9%) 0.011 ms/op
Iteration   2: 3.717 ±(99.9%) 0.008 ms/op
Iteration   3: 3.638 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.658 ±(99.9%) 0.941 ms/op [Average]
  (min, avg, max) = (3.620, 3.658, 3.717), stdev = 0.052
  CI (99.9%): [2.717, 4.600] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.335 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.008 ms/op
Iteration   1: 3.419 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.808 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   6.103 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  18.890 ms/op
                 createUser·p0.9999: 32.298 ms/op
                 createUser·p1.00:   32.342 ms/op

Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.281 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  10.826 ms/op
                 createUser·p0.9999: 29.127 ms/op
                 createUser·p1.00:   29.786 ms/op

Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  15.566 ms/op
                 createUser·p0.9999: 19.038 ms/op
                 createUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296666
  mean =      3.232 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20474 
    [ 2.500,  5.000) = 264749 
    [ 5.000,  7.500) = 10046 
    [ 7.500, 10.000) = 805 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     17.520 ms/op
     p(99.9900) =     30.583 ms/op
     p(99.9990) =     32.342 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.746 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.008 ms/op
Iteration   1: 2.990 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.162 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   3.879 ms/op
                 existUser·p0.999:  8.858 ms/op
                 existUser·p0.9999: 18.458 ms/op
                 existUser·p1.00:   19.137 ms/op

Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  17.564 ms/op
                 existUser·p0.9999: 21.725 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  13.964 ms/op
                 existUser·p0.9999: 16.680 ms/op
                 existUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 318502
  mean =      3.014 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21599 
    [ 2.500,  5.000) = 293454 
    [ 5.000,  7.500) = 2769 
    [ 7.500, 10.000) = 236 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.187 ms/op
     p(95.0000) =      3.334 ms/op
     p(99.0000) =      5.161 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     20.321 ms/op
     p(99.9990) =     22.014 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 8.337 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.009 ms/op
Iteration   1: 3.264 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  16.157 ms/op
                 getUser·p0.9999: 20.054 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   2: 3.270 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  8.964 ms/op
                 getUser·p0.9999: 28.220 ms/op
                 getUser·p1.00:   30.278 ms/op

Iteration   3: 3.193 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.612 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  14.762 ms/op
                 getUser·p0.9999: 22.740 ms/op
                 getUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296025
  mean =      3.242 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15055 
    [ 2.500,  5.000) = 271232 
    [ 5.000,  7.500) = 8796 
    [ 7.500, 10.000) = 495 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     15.154 ms/op
     p(99.9900) =     27.171 ms/op
     p(99.9990) =     30.055 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 8.880 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.750 ±(99.9%) 0.012 ms/op
Iteration   1: 3.697 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.405 ms/op
                 listUser·p0.999:  14.655 ms/op
                 listUser·p0.9999: 18.638 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   2: 3.731 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.706 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.976 ms/op
                 listUser·p0.9999: 17.105 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   3: 3.653 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.011 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   6.332 ms/op
                 listUser·p0.999:  11.510 ms/op
                 listUser·p0.9999: 18.153 ms/op
                 listUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259732
  mean =      3.693 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 96 
    [ 2.500,  3.750) = 211819 
    [ 3.750,  5.000) = 40171 
    [ 5.000,  6.250) = 3183 
    [ 6.250,  7.500) = 2746 
    [ 7.500,  8.750) = 834 
    [ 8.750, 10.000) = 263 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 174 
    [12.500, 13.750) = 126 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 67 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     13.046 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     19.039 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.634 ± 5.394  ops/ms
ClientPb.existUser                       thrpt       3  10.349 ± 3.555  ops/ms
ClientPb.getUser                         thrpt       3  10.313 ± 3.914  ops/ms
ClientPb.listUser                        thrpt       3   8.760 ± 3.036  ops/ms
ClientPb.createUser                       avgt       3   3.159 ± 0.089   ms/op
ClientPb.existUser                        avgt       3   3.041 ± 1.624   ms/op
ClientPb.getUser                          avgt       3   3.140 ± 1.610   ms/op
ClientPb.listUser                         avgt       3   3.658 ± 0.941   ms/op
ClientPb.createUser                     sample  296666   3.232 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.797           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.559           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.734           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.520           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.583           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.342           ms/op
ClientPb.existUser                      sample  318502   3.014 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.951           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.161           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.467           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.321           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.086           ms/op
ClientPb.getUser                        sample  296025   3.242 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.980           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.100           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.154           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.171           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.278           ms/op
ClientPb.listUser                       sample  259732   3.693 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.706           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.734           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.046           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.990           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.202           ms/op
