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
# Warmup Iteration   1: 2.679 ops/ms
# Warmup Iteration   2: 6.156 ops/ms
# Warmup Iteration   3: 9.430 ops/ms
Iteration   1: 9.736 ops/ms
Iteration   2: 9.652 ops/ms
Iteration   3: 10.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.914 ±(99.9%) 6.996 ops/ms [Average]
  (min, avg, max) = (9.652, 9.914, 10.354), stdev = 0.383
  CI (99.9%): [2.918, 16.910] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.835 ops/ms
# Warmup Iteration   2: 9.156 ops/ms
# Warmup Iteration   3: 10.340 ops/ms
Iteration   1: 10.911 ops/ms
Iteration   2: 10.670 ops/ms
Iteration   3: 9.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.472 ±(99.9%) 10.282 ops/ms [Average]
  (min, avg, max) = (9.837, 10.472, 10.911), stdev = 0.564
  CI (99.9%): [0.191, 20.754] (assumes normal distribution)


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
# Warmup Iteration   1: 3.182 ops/ms
# Warmup Iteration   2: 8.339 ops/ms
# Warmup Iteration   3: 9.774 ops/ms
Iteration   1: 10.041 ops/ms
Iteration   2: 9.951 ops/ms
Iteration   3: 9.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.864 ±(99.9%) 4.244 ops/ms [Average]
  (min, avg, max) = (9.600, 9.864, 10.041), stdev = 0.233
  CI (99.9%): [5.620, 14.109] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.489 ops/ms
# Warmup Iteration   2: 8.131 ops/ms
# Warmup Iteration   3: 8.601 ops/ms
Iteration   1: 8.814 ops/ms
Iteration   2: 8.789 ops/ms
Iteration   3: 8.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.769 ±(99.9%) 1.035 ops/ms [Average]
  (min, avg, max) = (8.706, 8.769, 8.814), stdev = 0.057
  CI (99.9%): [7.734, 9.805] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.105 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.471 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.005 ms/op
Iteration   1: 3.165 ±(99.9%) 0.003 ms/op
Iteration   2: 3.091 ±(99.9%) 0.002 ms/op
Iteration   3: 3.223 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.159 ±(99.9%) 1.205 ms/op [Average]
  (min, avg, max) = (3.091, 3.159, 3.223), stdev = 0.066
  CI (99.9%): [1.954, 4.365] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.581 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.005 ms/op
Iteration   1: 3.094 ±(99.9%) 0.007 ms/op
Iteration   2: 3.184 ±(99.9%) 0.005 ms/op
Iteration   3: 3.145 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.141 ±(99.9%) 0.823 ms/op [Average]
  (min, avg, max) = (3.094, 3.141, 3.184), stdev = 0.045
  CI (99.9%): [2.318, 3.964] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.594 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.004 ms/op
Iteration   1: 3.074 ±(99.9%) 0.005 ms/op
Iteration   2: 3.130 ±(99.9%) 0.004 ms/op
Iteration   3: 3.059 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.087 ±(99.9%) 0.685 ms/op [Average]
  (min, avg, max) = (3.059, 3.087, 3.130), stdev = 0.038
  CI (99.9%): [2.402, 3.773] (assumes normal distribution)


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
# Warmup Iteration   1: 9.429 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.679 ±(99.9%) 0.006 ms/op
Iteration   1: 3.715 ±(99.9%) 0.005 ms/op
Iteration   2: 3.714 ±(99.9%) 0.004 ms/op
Iteration   3: 3.618 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.682 ±(99.9%) 1.016 ms/op [Average]
  (min, avg, max) = (3.618, 3.682, 3.715), stdev = 0.056
  CI (99.9%): [2.666, 4.699] (assumes normal distribution)


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
# Warmup Iteration   1: 7.970 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.008 ms/op
Iteration   1: 3.127 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  12.955 ms/op
                 createUser·p0.9999: 19.759 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   2: 3.179 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  10.838 ms/op
                 createUser·p0.9999: 24.673 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   3: 3.179 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  15.835 ms/op
                 createUser·p0.9999: 26.211 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303428
  mean =      3.162 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16959 
    [ 2.500,  5.000) = 280489 
    [ 5.000,  7.500) = 4731 
    [ 7.500, 10.000) = 781 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     15.541 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 6.299 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.288 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.008 ms/op
Iteration   1: 3.012 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.146 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  8.075 ms/op
                 existUser·p0.9999: 18.035 ms/op
                 existUser·p1.00:   19.857 ms/op

Iteration   2: 3.087 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  12.878 ms/op
                 existUser·p0.9999: 22.401 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  8.741 ms/op
                 existUser·p0.9999: 19.287 ms/op
                 existUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313979
  mean =      3.056 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21333 
    [ 2.500,  5.000) = 286397 
    [ 5.000,  7.500) = 5604 
    [ 7.500, 10.000) = 278 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.265 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     12.243 ms/op
     p(99.9900) =     21.247 ms/op
     p(99.9990) =     22.802 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 8.015 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.009 ms/op
Iteration   1: 3.276 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.157 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 25.378 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   2: 3.305 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  14.173 ms/op
                 getUser·p0.9999: 35.455 ms/op
                 getUser·p1.00:   36.569 ms/op

Iteration   3: 3.208 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  8.905 ms/op
                 getUser·p0.9999: 23.724 ms/op
                 getUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294187
  mean =      3.263 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18485 
    [ 2.500,  5.000) = 266192 
    [ 5.000,  7.500) = 8270 
    [ 7.500, 10.000) = 766 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     15.313 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     36.569 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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
# Warmup Iteration   1: 9.558 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.036 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.011 ms/op
Iteration   1: 3.751 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 34.565 ms/op
                 listUser·p1.00:   37.618 ms/op

Iteration   2: 3.682 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.013 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.125 ms/op
                 listUser·p0.99:   7.424 ms/op
                 listUser·p0.999:  13.730 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 3.618 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.518 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.014 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 260578
  mean =      3.683 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 254262 
    [ 5.000,  7.500) = 4501 
    [ 7.500, 10.000) = 1094 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     14.359 ms/op
     p(99.9900) =     32.078 ms/op
     p(99.9990) =     35.622 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   9.914 ±  6.996  ops/ms
ClientPb.existUser                       thrpt       3  10.472 ± 10.282  ops/ms
ClientPb.getUser                         thrpt       3   9.864 ±  4.244  ops/ms
ClientPb.listUser                        thrpt       3   8.769 ±  1.035  ops/ms
ClientPb.createUser                       avgt       3   3.159 ±  1.205   ms/op
ClientPb.existUser                        avgt       3   3.141 ±  0.823   ms/op
ClientPb.getUser                          avgt       3   3.087 ±  0.685   ms/op
ClientPb.listUser                         avgt       3   3.682 ±  1.016   ms/op
ClientPb.createUser                     sample  303428   3.162 ±  0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.094            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.072            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.539            ms/op
ClientPb.createUser:createUser·p0.95    sample           3.940            ms/op
ClientPb.createUser:createUser·p0.99    sample           5.718            ms/op
ClientPb.createUser:createUser·p0.999   sample          15.541            ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.707            ms/op
ClientPb.createUser:createUser·p1.00    sample          26.542            ms/op
ClientPb.existUser                      sample  313979   3.056 ±  0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.964            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.002            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.265            ms/op
ClientPb.existUser:existUser·p0.95      sample           3.830            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.325            ms/op
ClientPb.existUser:existUser·p0.999     sample          12.243            ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.247            ms/op
ClientPb.existUser:existUser·p1.00      sample          23.233            ms/op
ClientPb.getUser                        sample  294187   3.263 ±  0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.824            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.666            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.242            ms/op
ClientPb.getUser:getUser·p0.999         sample          15.313            ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.406            ms/op
ClientPb.getUser:getUser·p1.00          sample          36.569            ms/op
ClientPb.listUser                       sample  260578   3.683 ±  0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.272            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.559            ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.227            ms/op
ClientPb.listUser:listUser·p0.99        sample           6.791            ms/op
ClientPb.listUser:listUser·p0.999       sample          14.359            ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.078            ms/op
ClientPb.listUser:listUser·p1.00        sample          37.618            ms/op
