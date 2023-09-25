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
# Warmup Iteration   1: 2.372 ops/ms
# Warmup Iteration   2: 5.063 ops/ms
# Warmup Iteration   3: 9.134 ops/ms
Iteration   1: 9.685 ops/ms
Iteration   2: 9.857 ops/ms
Iteration   3: 9.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.728 ±(99.9%) 2.071 ops/ms [Average]
  (min, avg, max) = (9.643, 9.728, 9.857), stdev = 0.114
  CI (99.9%): [7.657, 11.800] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.556 ops/ms
# Warmup Iteration   2: 9.332 ops/ms
# Warmup Iteration   3: 10.031 ops/ms
Iteration   1: 10.123 ops/ms
Iteration   2: 9.952 ops/ms
Iteration   3: 10.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.090 ±(99.9%) 2.271 ops/ms [Average]
  (min, avg, max) = (9.952, 10.090, 10.194), stdev = 0.125
  CI (99.9%): [7.818, 12.361] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.374 ops/ms
# Warmup Iteration   2: 9.154 ops/ms
# Warmup Iteration   3: 9.613 ops/ms
Iteration   1: 9.670 ops/ms
Iteration   2: 9.762 ops/ms
Iteration   3: 9.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.791 ±(99.9%) 2.524 ops/ms [Average]
  (min, avg, max) = (9.670, 9.791, 9.942), stdev = 0.138
  CI (99.9%): [7.267, 12.316] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.301 ops/ms
# Warmup Iteration   2: 7.519 ops/ms
# Warmup Iteration   3: 8.032 ops/ms
Iteration   1: 8.180 ops/ms
Iteration   2: 8.119 ops/ms
Iteration   3: 8.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.142 ±(99.9%) 0.616 ops/ms [Average]
  (min, avg, max) = (8.119, 8.142, 8.180), stdev = 0.034
  CI (99.9%): [7.526, 8.757] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 9.391 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.002 ms/op
Iteration   1: 3.348 ±(99.9%) 0.005 ms/op
Iteration   2: 3.415 ±(99.9%) 0.002 ms/op
Iteration   3: 3.306 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.356 ±(99.9%) 1.001 ms/op [Average]
  (min, avg, max) = (3.306, 3.356, 3.415), stdev = 0.055
  CI (99.9%): [2.355, 4.358] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.804 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.002 ms/op
Iteration   1: 3.157 ±(99.9%) 0.004 ms/op
Iteration   2: 3.168 ±(99.9%) 0.003 ms/op
Iteration   3: 3.206 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.177 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (3.157, 3.177, 3.206), stdev = 0.026
  CI (99.9%): [2.709, 3.646] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.872 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.409 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.002 ms/op
Iteration   1: 3.298 ±(99.9%) 0.003 ms/op
Iteration   2: 3.321 ±(99.9%) 0.002 ms/op
Iteration   3: 3.275 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.298 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (3.275, 3.298, 3.321), stdev = 0.023
  CI (99.9%): [2.873, 3.723] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.615 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.266 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.004 ms/op
Iteration   1: 3.856 ±(99.9%) 0.003 ms/op
Iteration   2: 3.804 ±(99.9%) 0.004 ms/op
Iteration   3: 3.829 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.830 ±(99.9%) 0.466 ms/op [Average]
  (min, avg, max) = (3.804, 3.830, 3.856), stdev = 0.026
  CI (99.9%): [3.363, 4.296] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.861 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.008 ms/op
Iteration   1: 3.311 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  14.252 ms/op
                 createUser·p0.9999: 22.271 ms/op
                 createUser·p1.00:   23.822 ms/op

Iteration   2: 3.298 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.260 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.463 ms/op
                 createUser·p0.999:  20.152 ms/op
                 createUser·p0.9999: 23.439 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   3: 3.310 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.300 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  15.274 ms/op
                 createUser·p0.9999: 27.372 ms/op
                 createUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290237
  mean =      3.306 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13838 
    [ 2.500,  5.000) = 271906 
    [ 5.000,  7.500) = 3728 
    [ 7.500, 10.000) = 212 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     16.626 ms/op
     p(99.9900) =     23.818 ms/op
     p(99.9990) =     27.460 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.118 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.345 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.009 ms/op
Iteration   1: 3.126 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.327 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  8.066 ms/op
                 existUser·p0.9999: 18.713 ms/op
                 existUser·p1.00:   19.235 ms/op

Iteration   2: 3.122 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  13.631 ms/op
                 existUser·p0.9999: 22.546 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   3: 3.195 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.497 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  13.631 ms/op
                 existUser·p0.9999: 22.249 ms/op
                 existUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304733
  mean =      3.147 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14308 
    [ 2.500,  5.000) = 285877 
    [ 5.000,  7.500) = 3973 
    [ 7.500, 10.000) = 158 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     13.603 ms/op
     p(99.9900) =     22.022 ms/op
     p(99.9990) =     23.552 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.701 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.603 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.010 ms/op
Iteration   1: 3.277 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   6.648 ms/op
                 getUser·p0.999:  18.547 ms/op
                 getUser·p0.9999: 20.480 ms/op
                 getUser·p1.00:   21.922 ms/op

Iteration   2: 3.338 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   6.347 ms/op
                 getUser·p0.999:  18.293 ms/op
                 getUser·p0.9999: 22.427 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   3: 3.339 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.419 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  14.057 ms/op
                 getUser·p0.9999: 20.212 ms/op
                 getUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289342
  mean =      3.318 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6844 
    [ 2.500,  5.000) = 275420 
    [ 5.000,  7.500) = 5699 
    [ 7.500, 10.000) = 682 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 175 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     16.799 ms/op
     p(99.9900) =     21.203 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.101 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.234 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.012 ms/op
Iteration   1: 4.007 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.389 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  17.386 ms/op
                 listUser·p0.9999: 21.266 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   2: 3.914 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.615 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   3: 3.903 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.692 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   6.672 ms/op
                 listUser·p0.999:  13.312 ms/op
                 listUser·p0.9999: 16.053 ms/op
                 listUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243454
  mean =      3.941 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 235677 
    [ 5.000,  7.500) = 6217 
    [ 7.500, 10.000) = 802 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 326 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.483 ms/op
     p(99.9900) =     20.447 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.728 ± 2.071  ops/ms
ClientPb.existUser                       thrpt       3  10.090 ± 2.271  ops/ms
ClientPb.getUser                         thrpt       3   9.791 ± 2.524  ops/ms
ClientPb.listUser                        thrpt       3   8.142 ± 0.616  ops/ms
ClientPb.createUser                       avgt       3   3.356 ± 1.001   ms/op
ClientPb.existUser                        avgt       3   3.177 ± 0.469   ms/op
ClientPb.getUser                          avgt       3   3.298 ± 0.425   ms/op
ClientPb.listUser                         avgt       3   3.830 ± 0.466   ms/op
ClientPb.createUser                     sample  290237   3.306 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.260           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.690           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.628           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.626           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.818           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.492           ms/op
ClientPb.existUser                      sample  304733   3.147 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.945           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.428           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.603           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.022           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.921           ms/op
ClientPb.getUser                        sample  289342   3.318 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.202           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.654           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.595           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.799           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.203           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.364           ms/op
ClientPb.listUser                       sample  243454   3.941 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.389           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.483           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.447           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.020           ms/op
