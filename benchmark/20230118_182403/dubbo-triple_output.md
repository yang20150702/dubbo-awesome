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
# Warmup Iteration   1: 2.587 ops/ms
# Warmup Iteration   2: 6.472 ops/ms
# Warmup Iteration   3: 9.256 ops/ms
Iteration   1: 9.826 ops/ms
Iteration   2: 9.912 ops/ms
Iteration   3: 9.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.827 ±(99.9%) 1.542 ops/ms [Average]
  (min, avg, max) = (9.743, 9.827, 9.912), stdev = 0.085
  CI (99.9%): [8.285, 11.369] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.728 ops/ms
# Warmup Iteration   2: 9.573 ops/ms
# Warmup Iteration   3: 10.357 ops/ms
Iteration   1: 10.678 ops/ms
Iteration   2: 10.312 ops/ms
Iteration   3: 10.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.480 ±(99.9%) 3.369 ops/ms [Average]
  (min, avg, max) = (10.312, 10.480, 10.678), stdev = 0.185
  CI (99.9%): [7.112, 13.849] (assumes normal distribution)


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
# Warmup Iteration   1: 3.674 ops/ms
# Warmup Iteration   2: 9.255 ops/ms
# Warmup Iteration   3: 10.107 ops/ms
Iteration   1: 9.978 ops/ms
Iteration   2: 10.034 ops/ms
Iteration   3: 9.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.978 ±(99.9%) 1.005 ops/ms [Average]
  (min, avg, max) = (9.924, 9.978, 10.034), stdev = 0.055
  CI (99.9%): [8.974, 10.983] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.584 ops/ms
# Warmup Iteration   2: 7.978 ops/ms
# Warmup Iteration   3: 8.360 ops/ms
Iteration   1: 8.364 ops/ms
Iteration   2: 8.586 ops/ms
Iteration   3: 8.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.514 ±(99.9%) 2.369 ops/ms [Average]
  (min, avg, max) = (8.364, 8.514, 8.592), stdev = 0.130
  CI (99.9%): [6.145, 10.883] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.332 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.400 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.006 ms/op
Iteration   1: 3.170 ±(99.9%) 0.003 ms/op
Iteration   2: 3.063 ±(99.9%) 0.009 ms/op
Iteration   3: 3.075 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.103 ±(99.9%) 1.070 ms/op [Average]
  (min, avg, max) = (3.063, 3.103, 3.170), stdev = 0.059
  CI (99.9%): [2.033, 4.173] (assumes normal distribution)


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
# Warmup Iteration   1: 6.358 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.359 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.002 ms/op
Iteration   1: 3.102 ±(99.9%) 0.006 ms/op
Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
Iteration   3: 3.191 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.131 ±(99.9%) 0.955 ms/op [Average]
  (min, avg, max) = (3.099, 3.131, 3.191), stdev = 0.052
  CI (99.9%): [2.175, 4.086] (assumes normal distribution)


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
# Warmup Iteration   1: 6.654 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.004 ms/op
Iteration   1: 3.137 ±(99.9%) 0.004 ms/op
Iteration   2: 3.172 ±(99.9%) 0.006 ms/op
Iteration   3: 3.071 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.127 ±(99.9%) 0.935 ms/op [Average]
  (min, avg, max) = (3.071, 3.127, 3.172), stdev = 0.051
  CI (99.9%): [2.192, 4.062] (assumes normal distribution)


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
# Warmup Iteration   1: 8.283 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.004 ms/op
Iteration   1: 3.835 ±(99.9%) 0.009 ms/op
Iteration   2: 3.783 ±(99.9%) 0.006 ms/op
Iteration   3: 3.666 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.761 ±(99.9%) 1.585 ms/op [Average]
  (min, avg, max) = (3.666, 3.761, 3.835), stdev = 0.087
  CI (99.9%): [2.176, 5.346] (assumes normal distribution)


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
# Warmup Iteration   1: 6.884 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 3.927 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.009 ms/op
Iteration   1: 3.111 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.448 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  14.046 ms/op
                 createUser·p0.9999: 19.815 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   2: 3.235 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.595 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  9.558 ms/op
                 createUser·p0.9999: 21.692 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   3: 3.223 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   5.210 ms/op
                 createUser·p0.999:  15.423 ms/op
                 createUser·p0.9999: 21.692 ms/op
                 createUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300858
  mean =      3.189 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19551 
    [ 2.500,  5.000) = 274620 
    [ 5.000,  7.500) = 5655 
    [ 7.500, 10.000) = 543 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.680 ms/op
     p(99.9000) =     15.237 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     22.216 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 8.067 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.284 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.008 ms/op
Iteration   1: 3.008 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  9.978 ms/op
                 existUser·p0.9999: 18.288 ms/op
                 existUser·p1.00:   18.973 ms/op

Iteration   2: 3.053 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  10.554 ms/op
                 existUser·p0.9999: 22.479 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   3: 3.198 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.264 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  11.976 ms/op
                 existUser·p0.9999: 20.283 ms/op
                 existUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311174
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24493 
    [ 2.500,  5.000) = 281614 
    [ 5.000,  7.500) = 4431 
    [ 7.500, 10.000) = 263 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.018 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     11.420 ms/op
     p(99.9900) =     21.633 ms/op
     p(99.9990) =     22.672 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 6.952 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.009 ms/op
Iteration   1: 3.275 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  14.840 ms/op
                 getUser·p0.9999: 20.003 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.618 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  7.766 ms/op
                 getUser·p0.9999: 20.704 ms/op
                 getUser·p1.00:   20.906 ms/op

Iteration   3: 3.183 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.489 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   5.732 ms/op
                 getUser·p0.999:  13.877 ms/op
                 getUser·p0.9999: 20.898 ms/op
                 getUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300179
  mean =      3.198 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18261 
    [ 2.500,  5.000) = 275301 
    [ 5.000,  7.500) = 5732 
    [ 7.500, 10.000) = 470 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 157 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     13.918 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 8.673 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.757 ±(99.9%) 0.011 ms/op
Iteration   1: 3.717 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  14.448 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   2: 3.761 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.671 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  14.270 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   3: 3.848 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  13.631 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254366
  mean =      3.774 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 102 
    [ 2.500,  5.000) = 244206 
    [ 5.000,  7.500) = 8042 
    [ 7.500, 10.000) = 1203 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 338 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     14.232 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     22.199 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.827 ± 1.542  ops/ms
ClientPb.existUser                       thrpt       3  10.480 ± 3.369  ops/ms
ClientPb.getUser                         thrpt       3   9.978 ± 1.005  ops/ms
ClientPb.listUser                        thrpt       3   8.514 ± 2.369  ops/ms
ClientPb.createUser                       avgt       3   3.103 ± 1.070   ms/op
ClientPb.existUser                        avgt       3   3.131 ± 0.955   ms/op
ClientPb.getUser                          avgt       3   3.127 ± 0.935   ms/op
ClientPb.listUser                         avgt       3   3.761 ± 1.585   ms/op
ClientPb.createUser                     sample  300858   3.189 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.219           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.527           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.680           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.237           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.692           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.117           ms/op
ClientPb.existUser                      sample  311174   3.084 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.018           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.367           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.276           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.420           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.633           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.938           ms/op
ClientPb.getUser                        sample  300179   3.198 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.448           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.633           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.693           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.918           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.644           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.987           ms/op
ClientPb.listUser                       sample  254366   3.774 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.063           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.062           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.232           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.332           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.282           ms/op
