# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.073 ops/ms
# Warmup Iteration   2: 4.958 ops/ms
# Warmup Iteration   3: 8.629 ops/ms
Iteration   1: 9.133 ops/ms
Iteration   2: 9.245 ops/ms
Iteration   3: 9.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.158 ±(99.9%) 1.429 ops/ms [Average]
  (min, avg, max) = (9.095, 9.158, 9.245), stdev = 0.078
  CI (99.9%): [7.729, 10.587] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.859 ops/ms
# Warmup Iteration   2: 8.849 ops/ms
# Warmup Iteration   3: 9.479 ops/ms
Iteration   1: 9.646 ops/ms
Iteration   2: 9.371 ops/ms
Iteration   3: 9.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.559 ±(99.9%) 2.983 ops/ms [Average]
  (min, avg, max) = (9.371, 9.559, 9.661), stdev = 0.164
  CI (99.9%): [6.576, 12.542] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.976 ops/ms
# Warmup Iteration   2: 8.517 ops/ms
# Warmup Iteration   3: 8.976 ops/ms
Iteration   1: 9.226 ops/ms
Iteration   2: 9.386 ops/ms
Iteration   3: 9.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.300 ±(99.9%) 1.472 ops/ms [Average]
  (min, avg, max) = (9.226, 9.300, 9.386), stdev = 0.081
  CI (99.9%): [7.828, 10.771] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.291 ops/ms
# Warmup Iteration   2: 6.985 ops/ms
# Warmup Iteration   3: 7.698 ops/ms
Iteration   1: 7.675 ops/ms
Iteration   2: 7.696 ops/ms
Iteration   3: 7.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.694 ±(99.9%) 0.338 ops/ms [Average]
  (min, avg, max) = (7.675, 7.694, 7.712), stdev = 0.019
  CI (99.9%): [7.357, 8.032] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.043 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.004 ms/op
Iteration   1: 3.480 ±(99.9%) 0.006 ms/op
Iteration   2: 3.475 ±(99.9%) 0.004 ms/op
Iteration   3: 3.512 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.489 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (3.475, 3.489, 3.512), stdev = 0.020
  CI (99.9%): [3.125, 3.853] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.851 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.004 ms/op
Iteration   1: 3.266 ±(99.9%) 0.005 ms/op
Iteration   2: 3.280 ±(99.9%) 0.005 ms/op
Iteration   3: 3.341 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.295 ±(99.9%) 0.727 ms/op [Average]
  (min, avg, max) = (3.266, 3.295, 3.341), stdev = 0.040
  CI (99.9%): [2.568, 4.022] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.218 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.691 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.005 ms/op
Iteration   1: 3.416 ±(99.9%) 0.004 ms/op
Iteration   2: 3.429 ±(99.9%) 0.004 ms/op
Iteration   3: 3.447 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.431 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (3.416, 3.431, 3.447), stdev = 0.016
  CI (99.9%): [3.145, 3.716] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.772 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.433 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.251 ±(99.9%) 0.008 ms/op
Iteration   1: 4.072 ±(99.9%) 0.007 ms/op
Iteration   2: 4.099 ±(99.9%) 0.006 ms/op
Iteration   3: 4.078 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.083 ±(99.9%) 0.264 ms/op [Average]
  (min, avg, max) = (4.072, 4.083, 4.099), stdev = 0.014
  CI (99.9%): [3.819, 4.347] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.366 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 3.942 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.716 ±(99.9%) 0.014 ms/op
Iteration   1: 3.394 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  19.331 ms/op
                 createUser·p0.9999: 22.036 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   2: 3.496 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.039 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  21.578 ms/op
                 createUser·p0.9999: 23.686 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   3: 3.536 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  19.104 ms/op
                 createUser·p0.9999: 28.702 ms/op
                 createUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276112
  mean =      3.474 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8372 
    [ 2.500,  5.000) = 260243 
    [ 5.000,  7.500) = 5870 
    [ 7.500, 10.000) = 885 
    [10.000, 12.500) = 288 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     19.198 ms/op
     p(99.9900) =     27.145 ms/op
     p(99.9990) =     29.638 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.817 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.010 ms/op
Iteration   1: 3.329 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   6.316 ms/op
                 existUser·p0.999:  19.447 ms/op
                 existUser·p0.9999: 22.459 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 3.449 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.212 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.916 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  22.479 ms/op
                 existUser·p0.9999: 27.165 ms/op
                 existUser·p1.00:   32.539 ms/op

Iteration   3: 3.426 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   6.775 ms/op
                 existUser·p0.999:  17.126 ms/op
                 existUser·p0.9999: 26.826 ms/op
                 existUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282290
  mean =      3.400 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11351 
    [ 2.500,  5.000) = 262361 
    [ 5.000,  7.500) = 7284 
    [ 7.500, 10.000) = 707 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     18.152 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     28.641 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.346 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.012 ms/op
Iteration   1: 3.574 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   7.922 ms/op
                 getUser·p0.999:  17.269 ms/op
                 getUser·p0.9999: 26.713 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   2: 3.550 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  14.730 ms/op
                 getUser·p0.9999: 29.852 ms/op
                 getUser·p1.00:   31.130 ms/op

Iteration   3: 3.489 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.922 ms/op
                 getUser·p0.999:  21.529 ms/op
                 getUser·p0.9999: 25.833 ms/op
                 getUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271249
  mean =      3.537 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6467 
    [ 2.500,  5.000) = 255799 
    [ 5.000,  7.500) = 6767 
    [ 7.500, 10.000) = 1317 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     29.254 ms/op
     p(99.9990) =     30.208 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.692 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.455 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.015 ms/op
Iteration   1: 4.188 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.944 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   8.290 ms/op
                 listUser·p0.999:  21.087 ms/op
                 listUser·p0.9999: 24.751 ms/op
                 listUser·p1.00:   26.804 ms/op

Iteration   2: 4.112 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  15.588 ms/op
                 listUser·p0.9999: 16.974 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   3: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  15.286 ms/op
                 listUser·p0.9999: 17.661 ms/op
                 listUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234538
  mean =      4.093 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 224192 
    [ 5.000,  7.500) = 7295 
    [ 7.500, 10.000) = 2073 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 332 
    [15.000, 17.500) = 333 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     15.794 ms/op
     p(99.9900) =     23.188 ms/op
     p(99.9990) =     25.522 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.158 ± 1.429  ops/ms
ClientPb.existUser                       thrpt       3   9.559 ± 2.983  ops/ms
ClientPb.getUser                         thrpt       3   9.300 ± 1.472  ops/ms
ClientPb.listUser                        thrpt       3   7.694 ± 0.338  ops/ms
ClientPb.createUser                       avgt       3   3.489 ± 0.364   ms/op
ClientPb.existUser                        avgt       3   3.295 ± 0.727   ms/op
ClientPb.getUser                          avgt       3   3.431 ± 0.286   ms/op
ClientPb.listUser                         avgt       3   4.083 ± 0.264   ms/op
ClientPb.createUser                     sample  276112   3.474 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.768           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.198           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.145           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.688           ms/op
ClientPb.existUser                      sample  282290   3.400 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.919           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.152           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.804           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.539           ms/op
ClientPb.getUser                        sample  271249   3.537 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.237           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.217           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.891           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.254           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.130           ms/op
ClientPb.listUser                       sample  234538   4.093 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.663           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.850           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.815           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.794           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.188           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.804           ms/op
