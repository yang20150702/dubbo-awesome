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
# Warmup Iteration   1: 2.668 ops/ms
# Warmup Iteration   2: 6.031 ops/ms
# Warmup Iteration   3: 9.224 ops/ms
Iteration   1: 9.402 ops/ms
Iteration   2: 9.477 ops/ms
Iteration   3: 10.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.629 ±(99.9%) 6.039 ops/ms [Average]
  (min, avg, max) = (9.402, 9.629, 10.009), stdev = 0.331
  CI (99.9%): [3.590, 15.669] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.906 ops/ms
# Warmup Iteration   2: 9.674 ops/ms
# Warmup Iteration   3: 10.381 ops/ms
Iteration   1: 10.488 ops/ms
Iteration   2: 10.544 ops/ms
Iteration   3: 10.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.417 ±(99.9%) 3.171 ops/ms [Average]
  (min, avg, max) = (10.219, 10.417, 10.544), stdev = 0.174
  CI (99.9%): [7.246, 13.588] (assumes normal distribution)


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
# Warmup Iteration   1: 3.813 ops/ms
# Warmup Iteration   2: 9.263 ops/ms
# Warmup Iteration   3: 9.952 ops/ms
Iteration   1: 10.049 ops/ms
Iteration   2: 10.123 ops/ms
Iteration   3: 9.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.999 ±(99.9%) 2.831 ops/ms [Average]
  (min, avg, max) = (9.825, 9.999, 10.123), stdev = 0.155
  CI (99.9%): [7.168, 12.830] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.110 ops/ms
# Warmup Iteration   2: 7.552 ops/ms
# Warmup Iteration   3: 8.109 ops/ms
Iteration   1: 8.583 ops/ms
Iteration   2: 8.453 ops/ms
Iteration   3: 8.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.593 ±(99.9%) 2.653 ops/ms [Average]
  (min, avg, max) = (8.453, 8.593, 8.743), stdev = 0.145
  CI (99.9%): [5.939, 11.246] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.976 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.005 ms/op
Iteration   1: 3.315 ±(99.9%) 0.009 ms/op
Iteration   2: 3.332 ±(99.9%) 0.006 ms/op
Iteration   3: 3.108 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.252 ±(99.9%) 2.276 ms/op [Average]
  (min, avg, max) = (3.108, 3.252, 3.332), stdev = 0.125
  CI (99.9%): [0.975, 5.528] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.775 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.468 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.003 ms/op
Iteration   2: 3.065 ±(99.9%) 0.003 ms/op
Iteration   3: 3.063 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.056 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (3.039, 3.056, 3.065), stdev = 0.014
  CI (99.9%): [2.796, 3.316] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.826 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.416 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.006 ms/op
Iteration   1: 3.234 ±(99.9%) 0.002 ms/op
Iteration   2: 3.220 ±(99.9%) 0.003 ms/op
Iteration   3: 3.299 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.251 ±(99.9%) 0.768 ms/op [Average]
  (min, avg, max) = (3.220, 3.251, 3.299), stdev = 0.042
  CI (99.9%): [2.483, 4.019] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 9.222 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.122 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.849 ±(99.9%) 0.005 ms/op
Iteration   1: 3.721 ±(99.9%) 0.006 ms/op
Iteration   2: 3.822 ±(99.9%) 0.009 ms/op
Iteration   3: 3.731 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.758 ±(99.9%) 1.012 ms/op [Average]
  (min, avg, max) = (3.721, 3.758, 3.822), stdev = 0.055
  CI (99.9%): [2.746, 4.770] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.909 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.010 ms/op
Iteration   1: 3.207 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   5.506 ms/op
                 createUser·p0.999:  18.579 ms/op
                 createUser·p0.9999: 31.097 ms/op
                 createUser·p1.00:   31.588 ms/op

Iteration   2: 3.280 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  10.232 ms/op
                 createUser·p0.9999: 23.667 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   3: 3.268 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   4.025 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  16.266 ms/op
                 createUser·p0.9999: 19.825 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295153
  mean =      3.251 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19456 
    [ 2.500,  5.000) = 269394 
    [ 5.000,  7.500) = 5250 
    [ 7.500, 10.000) = 556 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 182 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     17.329 ms/op
     p(99.9900) =     28.655 ms/op
     p(99.9990) =     31.493 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.999 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.433 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.233 ±(99.9%) 0.008 ms/op
Iteration   1: 3.233 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  13.074 ms/op
                 existUser·p0.9999: 27.595 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   2: 3.224 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  15.041 ms/op
                 existUser·p0.9999: 21.728 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   3: 3.171 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.448 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  13.074 ms/op
                 existUser·p0.9999: 21.227 ms/op
                 existUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298950
  mean =      3.209 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21199 
    [ 2.500,  5.000) = 272016 
    [ 5.000,  7.500) = 4785 
    [ 7.500, 10.000) = 410 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.995 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     26.906 ms/op
     p(99.9990) =     28.117 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 7.652 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.009 ms/op
Iteration   1: 3.214 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  18.121 ms/op
                 getUser·p0.9999: 23.364 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   2: 3.316 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.544 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  17.285 ms/op
                 getUser·p0.9999: 25.461 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   3: 3.207 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  10.256 ms/op
                 getUser·p0.9999: 22.392 ms/op
                 getUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295491
  mean =      3.245 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17077 
    [ 2.500,  5.000) = 270431 
    [ 5.000,  7.500) = 6899 
    [ 7.500, 10.000) = 597 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     16.679 ms/op
     p(99.9900) =     24.293 ms/op
     p(99.9990) =     25.760 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 8.758 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.690 ±(99.9%) 0.011 ms/op
Iteration   1: 3.727 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.937 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  15.905 ms/op
                 listUser·p0.9999: 19.576 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   2: 3.707 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  13.418 ms/op
                 listUser·p0.9999: 25.788 ms/op
                 listUser·p1.00:   29.262 ms/op

Iteration   3: 3.682 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  13.156 ms/op
                 listUser·p0.9999: 17.640 ms/op
                 listUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258739
  mean =      3.705 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 252204 
    [ 5.000,  7.500) = 4639 
    [ 7.500, 10.000) = 1228 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.937 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     19.374 ms/op
     p(99.9990) =     29.262 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.629 ± 6.039  ops/ms
ClientPb.existUser                       thrpt       3  10.417 ± 3.171  ops/ms
ClientPb.getUser                         thrpt       3   9.999 ± 2.831  ops/ms
ClientPb.listUser                        thrpt       3   8.593 ± 2.653  ops/ms
ClientPb.createUser                       avgt       3   3.252 ± 2.276   ms/op
ClientPb.existUser                        avgt       3   3.056 ± 0.260   ms/op
ClientPb.getUser                          avgt       3   3.251 ± 0.768   ms/op
ClientPb.listUser                         avgt       3   3.758 ± 1.012   ms/op
ClientPb.createUser                     sample  295153   3.251 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.901           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.641           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.329           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.655           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.588           ms/op
ClientPb.existUser                      sample  298950   3.209 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.995           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.254           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.906           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.377           ms/op
ClientPb.getUser                        sample  295491   3.245 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.947           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.641           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.153           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.939           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.679           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.293           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.985           ms/op
ClientPb.listUser                       sample  258739   3.705 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.937           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.617           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.402           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.374           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.262           ms/op
