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
# Warmup Iteration   1: 2.581 ops/ms
# Warmup Iteration   2: 5.548 ops/ms
# Warmup Iteration   3: 8.895 ops/ms
Iteration   1: 9.778 ops/ms
Iteration   2: 9.662 ops/ms
Iteration   3: 10.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.940 ±(99.9%) 7.025 ops/ms [Average]
  (min, avg, max) = (9.662, 9.940, 10.379), stdev = 0.385
  CI (99.9%): [2.915, 16.965] (assumes normal distribution)


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
# Warmup Iteration   1: 3.486 ops/ms
# Warmup Iteration   2: 9.559 ops/ms
# Warmup Iteration   3: 10.317 ops/ms
Iteration   1: 10.073 ops/ms
Iteration   2: 10.702 ops/ms
Iteration   3: 10.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.525 ±(99.9%) 7.192 ops/ms [Average]
  (min, avg, max) = (10.073, 10.525, 10.800), stdev = 0.394
  CI (99.9%): [3.333, 17.717] (assumes normal distribution)


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
# Warmup Iteration   1: 3.935 ops/ms
# Warmup Iteration   2: 9.292 ops/ms
# Warmup Iteration   3: 10.077 ops/ms
Iteration   1: 10.079 ops/ms
Iteration   2: 10.304 ops/ms
Iteration   3: 10.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.291 ±(99.9%) 3.747 ops/ms [Average]
  (min, avg, max) = (10.079, 10.291, 10.490), stdev = 0.205
  CI (99.9%): [6.544, 14.038] (assumes normal distribution)


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
# Warmup Iteration   1: 3.426 ops/ms
# Warmup Iteration   2: 7.895 ops/ms
# Warmup Iteration   3: 8.431 ops/ms
Iteration   1: 8.696 ops/ms
Iteration   2: 8.690 ops/ms
Iteration   3: 8.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.719 ±(99.9%) 0.823 ops/ms [Average]
  (min, avg, max) = (8.690, 8.719, 8.771), stdev = 0.045
  CI (99.9%): [7.896, 9.542] (assumes normal distribution)


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
# Warmup Iteration   1: 8.614 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.415 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.257 ±(99.9%) 0.002 ms/op
Iteration   1: 3.121 ±(99.9%) 0.002 ms/op
Iteration   2: 3.050 ±(99.9%) 0.005 ms/op
Iteration   3: 3.278 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.149 ±(99.9%) 2.130 ms/op [Average]
  (min, avg, max) = (3.050, 3.149, 3.278), stdev = 0.117
  CI (99.9%): [1.020, 5.279] (assumes normal distribution)


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
# Warmup Iteration   1: 7.159 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.345 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.001 ms/op
Iteration   1: 3.071 ±(99.9%) 0.006 ms/op
Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
Iteration   3: 3.185 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.098 ±(99.9%) 1.421 ms/op [Average]
  (min, avg, max) = (3.036, 3.098, 3.185), stdev = 0.078
  CI (99.9%): [1.677, 4.519] (assumes normal distribution)


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
# Warmup Iteration   1: 8.549 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.395 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.004 ms/op
Iteration   1: 3.102 ±(99.9%) 0.002 ms/op
Iteration   2: 3.097 ±(99.9%) 0.009 ms/op
Iteration   3: 3.058 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.086 ±(99.9%) 0.440 ms/op [Average]
  (min, avg, max) = (3.058, 3.086, 3.102), stdev = 0.024
  CI (99.9%): [2.645, 3.526] (assumes normal distribution)


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
# Warmup Iteration   1: 9.161 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.006 ms/op
Iteration   1: 3.673 ±(99.9%) 0.005 ms/op
Iteration   2: 3.668 ±(99.9%) 0.007 ms/op
Iteration   3: 3.598 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.647 ±(99.9%) 0.769 ms/op [Average]
  (min, avg, max) = (3.598, 3.647, 3.673), stdev = 0.042
  CI (99.9%): [2.878, 4.416] (assumes normal distribution)


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
# Warmup Iteration   1: 8.985 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.008 ms/op
Iteration   1: 3.117 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.322 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  18.416 ms/op
                 createUser·p0.9999: 20.406 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.165 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.285 ms/op
                 createUser·p0.95:   3.535 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  11.741 ms/op
                 createUser·p0.9999: 23.872 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   3: 3.110 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.655 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.281 ms/op
                 createUser·p0.95:   3.359 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  8.241 ms/op
                 createUser·p0.9999: 17.039 ms/op
                 createUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 307740
  mean =      3.118 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28937 
    [ 2.500,  5.000) = 274658 
    [ 5.000,  7.500) = 3453 
    [ 7.500, 10.000) = 260 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     23.305 ms/op
     p(99.9990) =     24.533 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 6.906 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.289 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.008 ms/op
Iteration   1: 3.051 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.195 ms/op
                 existUser·p0.95:   3.301 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  12.738 ms/op
                 existUser·p0.9999: 24.347 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   2: 3.006 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.150 ms/op
                 existUser·p0.95:   3.375 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  9.224 ms/op
                 existUser·p0.9999: 21.573 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   3: 3.042 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.530 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  13.713 ms/op
                 existUser·p0.9999: 19.579 ms/op
                 existUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 316343
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22455 
    [ 2.500,  5.000) = 288408 
    [ 5.000,  7.500) = 4480 
    [ 7.500, 10.000) = 472 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.187 ms/op
     p(95.0000) =      3.416 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     22.917 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 8.101 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.444 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.010 ms/op
Iteration   1: 3.228 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  12.350 ms/op
                 getUser·p0.9999: 19.806 ms/op
                 getUser·p1.00:   23.069 ms/op

Iteration   2: 3.081 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.245 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.334 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  17.905 ms/op
                 getUser·p0.9999: 26.190 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   3: 3.198 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  11.878 ms/op
                 getUser·p0.9999: 19.268 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302972
  mean =      3.168 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18228 
    [ 2.500,  5.000) = 279236 
    [ 5.000,  7.500) = 4491 
    [ 7.500, 10.000) = 537 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 185 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.245 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.798 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     15.843 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     27.849 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 8.604 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.013 ms/op
Iteration   1: 3.807 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.647 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   5.275 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 20.428 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   2: 3.861 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  13.208 ms/op
                 listUser·p0.9999: 13.964 ms/op
                 listUser·p1.00:   14.631 ms/op

Iteration   3: 3.735 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.752 ms/op
                 listUser·p0.999:  13.533 ms/op
                 listUser·p0.9999: 16.510 ms/op
                 listUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252391
  mean =      3.800 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 242046 
    [ 5.000,  7.500) = 7494 
    [ 7.500, 10.000) = 2014 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 294 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.647 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     19.194 ms/op
     p(99.9990) =     20.982 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.940 ± 7.025  ops/ms
ClientPb.existUser                       thrpt       3  10.525 ± 7.192  ops/ms
ClientPb.getUser                         thrpt       3  10.291 ± 3.747  ops/ms
ClientPb.listUser                        thrpt       3   8.719 ± 0.823  ops/ms
ClientPb.createUser                       avgt       3   3.149 ± 2.130   ms/op
ClientPb.existUser                        avgt       3   3.098 ± 1.421   ms/op
ClientPb.getUser                          avgt       3   3.086 ± 0.440   ms/op
ClientPb.listUser                         avgt       3   3.647 ± 0.769   ms/op
ClientPb.createUser                     sample  307740   3.118 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.057           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.535           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.189           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.305           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.805           ms/op
ClientPb.existUser                      sample  316343   3.033 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.664           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.416           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.554           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.533           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.917           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.395           ms/op
ClientPb.getUser                        sample  302972   3.168 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.245           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.523           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.798           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.530           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.843           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.839           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.017           ms/op
ClientPb.listUser                       sample  252391   3.800 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.647           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.627           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.352           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.194           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.201           ms/op
