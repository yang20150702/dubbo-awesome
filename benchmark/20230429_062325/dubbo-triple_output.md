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
# Warmup Iteration   1: 2.512 ops/ms
# Warmup Iteration   2: 6.162 ops/ms
# Warmup Iteration   3: 9.659 ops/ms
Iteration   1: 9.970 ops/ms
Iteration   2: 10.248 ops/ms
Iteration   3: 10.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.076 ±(99.9%) 2.751 ops/ms [Average]
  (min, avg, max) = (9.970, 10.076, 10.248), stdev = 0.151
  CI (99.9%): [7.324, 12.827] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.813 ops/ms
# Warmup Iteration   2: 9.454 ops/ms
# Warmup Iteration   3: 10.131 ops/ms
Iteration   1: 10.163 ops/ms
Iteration   2: 10.424 ops/ms
Iteration   3: 10.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.409 ±(99.9%) 4.359 ops/ms [Average]
  (min, avg, max) = (10.163, 10.409, 10.641), stdev = 0.239
  CI (99.9%): [6.050, 14.768] (assumes normal distribution)


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
# Warmup Iteration   1: 3.824 ops/ms
# Warmup Iteration   2: 8.695 ops/ms
# Warmup Iteration   3: 9.603 ops/ms
Iteration   1: 9.783 ops/ms
Iteration   2: 9.813 ops/ms
Iteration   3: 9.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.835 ±(99.9%) 1.215 ops/ms [Average]
  (min, avg, max) = (9.783, 9.835, 9.910), stdev = 0.067
  CI (99.9%): [8.621, 11.050] (assumes normal distribution)


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
# Warmup Iteration   1: 3.688 ops/ms
# Warmup Iteration   2: 7.986 ops/ms
# Warmup Iteration   3: 8.354 ops/ms
Iteration   1: 8.501 ops/ms
Iteration   2: 8.576 ops/ms
Iteration   3: 8.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.548 ±(99.9%) 0.753 ops/ms [Average]
  (min, avg, max) = (8.501, 8.548, 8.576), stdev = 0.041
  CI (99.9%): [7.795, 9.301] (assumes normal distribution)


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
# Warmup Iteration   1: 7.925 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.557 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.348 ±(99.9%) 0.005 ms/op
Iteration   1: 3.274 ±(99.9%) 0.007 ms/op
Iteration   2: 3.198 ±(99.9%) 0.005 ms/op
Iteration   3: 3.159 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.210 ±(99.9%) 1.061 ms/op [Average]
  (min, avg, max) = (3.159, 3.210, 3.274), stdev = 0.058
  CI (99.9%): [2.149, 4.271] (assumes normal distribution)


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
# Warmup Iteration   1: 7.748 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.316 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.006 ms/op
Iteration   1: 2.956 ±(99.9%) 0.002 ms/op
Iteration   2: 3.048 ±(99.9%) 0.003 ms/op
Iteration   3: 3.013 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.006 ±(99.9%) 0.843 ms/op [Average]
  (min, avg, max) = (2.956, 3.006, 3.048), stdev = 0.046
  CI (99.9%): [2.163, 3.849] (assumes normal distribution)


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
# Warmup Iteration   1: 7.010 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.439 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.005 ms/op
Iteration   1: 3.188 ±(99.9%) 0.003 ms/op
Iteration   2: 3.111 ±(99.9%) 0.004 ms/op
Iteration   3: 3.145 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.148 ±(99.9%) 0.706 ms/op [Average]
  (min, avg, max) = (3.111, 3.148, 3.188), stdev = 0.039
  CI (99.9%): [2.442, 3.854] (assumes normal distribution)


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
# Warmup Iteration   1: 9.649 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.005 ms/op
Iteration   1: 3.707 ±(99.9%) 0.007 ms/op
Iteration   2: 3.775 ±(99.9%) 0.007 ms/op
Iteration   3: 3.842 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.775 ±(99.9%) 1.228 ms/op [Average]
  (min, avg, max) = (3.707, 3.775, 3.842), stdev = 0.067
  CI (99.9%): [2.547, 5.002] (assumes normal distribution)


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
# Warmup Iteration   1: 8.381 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.882 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.009 ms/op
Iteration   1: 3.185 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  13.828 ms/op
                 createUser·p0.9999: 19.923 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   2: 3.158 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  19.194 ms/op
                 createUser·p0.9999: 23.798 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   3: 3.263 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  14.254 ms/op
                 createUser·p0.9999: 23.560 ms/op
                 createUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299646
  mean =      3.202 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17287 
    [ 2.500,  5.000) = 276169 
    [ 5.000,  7.500) = 5211 
    [ 7.500, 10.000) = 438 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     14.669 ms/op
     p(99.9900) =     23.429 ms/op
     p(99.9990) =     24.576 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 7.006 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.309 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.007 ms/op
Iteration   1: 3.054 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  8.827 ms/op
                 existUser·p0.9999: 18.236 ms/op
                 existUser·p1.00:   19.235 ms/op

Iteration   2: 3.144 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.503 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  12.653 ms/op
                 existUser·p0.9999: 20.021 ms/op
                 existUser·p1.00:   20.349 ms/op

Iteration   3: 3.076 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.511 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   6.106 ms/op
                 existUser·p0.999:  11.157 ms/op
                 existUser·p0.9999: 22.367 ms/op
                 existUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310605
  mean =      3.091 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23116 
    [ 2.500,  5.000) = 281793 
    [ 5.000,  7.500) = 4751 
    [ 7.500, 10.000) = 495 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      5.570 ms/op
     p(99.9000) =     12.344 ms/op
     p(99.9900) =     21.297 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 6.800 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.473 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.010 ms/op
Iteration   1: 3.194 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.522 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.439 ms/op
                 getUser·p0.999:  16.564 ms/op
                 getUser·p0.9999: 19.857 ms/op
                 getUser·p1.00:   20.709 ms/op

Iteration   2: 3.117 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.100 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   5.498 ms/op
                 getUser·p0.999:  12.508 ms/op
                 getUser·p0.9999: 26.599 ms/op
                 getUser·p1.00:   27.558 ms/op

Iteration   3: 3.179 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.401 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  10.902 ms/op
                 getUser·p0.9999: 21.725 ms/op
                 getUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303281
  mean =      3.163 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20876 
    [ 2.500,  5.000) = 276891 
    [ 5.000,  7.500) = 4679 
    [ 7.500, 10.000) = 405 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     25.406 ms/op
     p(99.9990) =     26.932 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 8.191 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 4.195 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.761 ±(99.9%) 0.011 ms/op
Iteration   1: 3.752 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.748 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 26.018 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   2: 3.666 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.112 ms/op
                 listUser·p0.99:   5.865 ms/op
                 listUser·p0.999:  13.599 ms/op
                 listUser·p0.9999: 19.433 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 3.759 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  11.760 ms/op
                 listUser·p0.9999: 15.409 ms/op
                 listUser·p1.00:   15.466 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257543
  mean =      3.725 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 250799 
    [ 5.000,  7.500) = 4734 
    [ 7.500, 10.000) = 1217 
    [10.000, 12.500) = 328 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     14.098 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     26.051 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.076 ± 2.751  ops/ms
ClientPb.existUser                       thrpt       3  10.409 ± 4.359  ops/ms
ClientPb.getUser                         thrpt       3   9.835 ± 1.215  ops/ms
ClientPb.listUser                        thrpt       3   8.548 ± 0.753  ops/ms
ClientPb.createUser                       avgt       3   3.210 ± 1.061   ms/op
ClientPb.existUser                        avgt       3   3.006 ± 0.843   ms/op
ClientPb.getUser                          avgt       3   3.148 ± 0.706   ms/op
ClientPb.listUser                         avgt       3   3.775 ± 1.228   ms/op
ClientPb.createUser                     sample  299646   3.202 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.951           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.580           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.644           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.669           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.429           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.936           ms/op
ClientPb.existUser                      sample  310605   3.091 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.796           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.570           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.344           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.297           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.069           ms/op
ClientPb.getUser                        sample  303281   3.163 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.100           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.535           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.538           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.451           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.406           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.558           ms/op
ClientPb.listUser                       sample  257543   3.725 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.748           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.914           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.098           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.805           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.051           ms/op
