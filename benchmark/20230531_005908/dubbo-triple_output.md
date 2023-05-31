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
# Warmup Iteration   1: 2.115 ops/ms
# Warmup Iteration   2: 5.171 ops/ms
# Warmup Iteration   3: 8.702 ops/ms
Iteration   1: 9.388 ops/ms
Iteration   2: 9.540 ops/ms
Iteration   3: 9.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.395 ±(99.9%) 2.588 ops/ms [Average]
  (min, avg, max) = (9.256, 9.395, 9.540), stdev = 0.142
  CI (99.9%): [6.807, 11.982] (assumes normal distribution)


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
# Warmup Iteration   1: 2.822 ops/ms
# Warmup Iteration   2: 8.898 ops/ms
# Warmup Iteration   3: 9.268 ops/ms
Iteration   1: 9.983 ops/ms
Iteration   2: 9.691 ops/ms
Iteration   3: 9.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.825 ±(99.9%) 2.696 ops/ms [Average]
  (min, avg, max) = (9.691, 9.825, 9.983), stdev = 0.148
  CI (99.9%): [7.128, 12.521] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.542 ops/ms
# Warmup Iteration   2: 7.766 ops/ms
# Warmup Iteration   3: 8.755 ops/ms
Iteration   1: 9.553 ops/ms
Iteration   2: 9.528 ops/ms
Iteration   3: 9.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.436 ±(99.9%) 3.304 ops/ms [Average]
  (min, avg, max) = (9.227, 9.436, 9.553), stdev = 0.181
  CI (99.9%): [6.132, 12.740] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.590 ops/ms
# Warmup Iteration   2: 6.874 ops/ms
# Warmup Iteration   3: 7.954 ops/ms
Iteration   1: 7.937 ops/ms
Iteration   2: 8.062 ops/ms
Iteration   3: 8.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.112 ±(99.9%) 3.753 ops/ms [Average]
  (min, avg, max) = (7.937, 8.112, 8.339), stdev = 0.206
  CI (99.9%): [4.360, 11.865] (assumes normal distribution)


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
# Warmup Iteration   1: 9.958 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.005 ms/op
Iteration   1: 3.440 ±(99.9%) 0.005 ms/op
Iteration   2: 3.386 ±(99.9%) 0.007 ms/op
Iteration   3: 3.381 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.402 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (3.381, 3.402, 3.440), stdev = 0.033
  CI (99.9%): [2.804, 4.001] (assumes normal distribution)


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
# Warmup Iteration   1: 9.653 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.007 ms/op
Iteration   1: 3.189 ±(99.9%) 0.009 ms/op
Iteration   2: 3.187 ±(99.9%) 0.009 ms/op
Iteration   3: 3.309 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.228 ±(99.9%) 1.274 ms/op [Average]
  (min, avg, max) = (3.187, 3.228, 3.309), stdev = 0.070
  CI (99.9%): [1.954, 4.502] (assumes normal distribution)


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
# Warmup Iteration   1: 8.805 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.640 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.007 ms/op
Iteration   1: 3.383 ±(99.9%) 0.006 ms/op
Iteration   2: 3.361 ±(99.9%) 0.003 ms/op
Iteration   3: 3.383 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.376 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (3.361, 3.376, 3.383), stdev = 0.012
  CI (99.9%): [3.153, 3.598] (assumes normal distribution)


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
# Warmup Iteration   1: 11.185 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.339 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.014 ms/op
Iteration   1: 3.915 ±(99.9%) 0.014 ms/op
Iteration   2: 4.131 ±(99.9%) 0.006 ms/op
Iteration   3: 3.999 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.015 ±(99.9%) 1.980 ms/op [Average]
  (min, avg, max) = (3.915, 4.015, 4.131), stdev = 0.109
  CI (99.9%): [2.036, 5.995] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.028 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.925 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.009 ms/op
Iteration   1: 3.482 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  20.814 ms/op
                 createUser·p0.9999: 22.997 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   2: 3.389 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  22.525 ms/op
                 createUser·p0.9999: 24.758 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   3: 3.370 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.801 ms/op
                 createUser·p0.999:  15.166 ms/op
                 createUser·p0.9999: 25.718 ms/op
                 createUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280969
  mean =      3.413 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14346 
    [ 2.500,  5.000) = 260806 
    [ 5.000,  7.500) = 4631 
    [ 7.500, 10.000) = 706 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     15.436 ms/op
     p(99.9900) =     24.769 ms/op
     p(99.9990) =     26.422 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 8.386 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.366 ±(99.9%) 0.008 ms/op
Iteration   1: 3.296 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.661 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  11.164 ms/op
                 existUser·p0.9999: 23.285 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   2: 3.374 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.054 ms/op
                 existUser·p0.999:  19.235 ms/op
                 existUser·p0.9999: 37.224 ms/op
                 existUser·p1.00:   37.421 ms/op

Iteration   3: 3.300 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   5.686 ms/op
                 existUser·p0.999:  14.567 ms/op
                 existUser·p0.9999: 26.247 ms/op
                 existUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288986
  mean =      3.323 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7455 
    [ 2.500,  5.000) = 277309 
    [ 5.000,  7.500) = 3314 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     12.274 ms/op
     p(99.9900) =     36.176 ms/op
     p(99.9990) =     37.356 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


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
# Warmup Iteration   1: 9.972 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.826 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.582 ±(99.9%) 0.012 ms/op
Iteration   1: 3.454 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  21.178 ms/op
                 getUser·p0.9999: 23.101 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   2: 3.444 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  22.220 ms/op
                 getUser·p0.9999: 25.222 ms/op
                 getUser·p1.00:   26.018 ms/op

Iteration   3: 3.411 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.845 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  19.702 ms/op
                 getUser·p0.9999: 27.087 ms/op
                 getUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279286
  mean =      3.436 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4223 
    [ 2.500,  5.000) = 268795 
    [ 5.000,  7.500) = 5139 
    [ 7.500, 10.000) = 657 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     20.854 ms/op
     p(99.9900) =     25.730 ms/op
     p(99.9990) =     27.428 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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
# Warmup Iteration   1: 11.091 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.220 ±(99.9%) 0.015 ms/op
Iteration   1: 4.078 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  22.135 ms/op
                 listUser·p0.9999: 25.564 ms/op
                 listUser·p1.00:   28.410 ms/op

Iteration   2: 4.235 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  16.670 ms/op
                 listUser·p0.9999: 21.792 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   3: 4.095 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.572 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  15.139 ms/op
                 listUser·p0.9999: 22.852 ms/op
                 listUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232122
  mean =      4.135 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 218937 
    [ 5.000,  7.500) = 10689 
    [ 7.500, 10.000) = 1622 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     24.405 ms/op
     p(99.9990) =     27.529 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.395 ± 2.588  ops/ms
ClientPb.existUser                       thrpt       3   9.825 ± 2.696  ops/ms
ClientPb.getUser                         thrpt       3   9.436 ± 3.304  ops/ms
ClientPb.listUser                        thrpt       3   8.112 ± 3.753  ops/ms
ClientPb.createUser                       avgt       3   3.402 ± 0.599   ms/op
ClientPb.existUser                        avgt       3   3.228 ± 1.274   ms/op
ClientPb.getUser                          avgt       3   3.376 ± 0.223   ms/op
ClientPb.listUser                         avgt       3   4.015 ± 1.980   ms/op
ClientPb.createUser                     sample  280969   3.413 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.204           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.915           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.436           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.769           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.673           ms/op
ClientPb.existUser                      sample  288986   3.323 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.329           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.274           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.176           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.421           ms/op
ClientPb.getUser                        sample  279286   3.436 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.327           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.980           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.854           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.730           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.606           ms/op
ClientPb.listUser                       sample  232122   4.135 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.360           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.079           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.545           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.924           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.405           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.410           ms/op
