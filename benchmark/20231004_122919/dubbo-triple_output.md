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
# Warmup Iteration   1: 2.246 ops/ms
# Warmup Iteration   2: 5.290 ops/ms
# Warmup Iteration   3: 9.173 ops/ms
Iteration   1: 9.643 ops/ms
Iteration   2: 9.797 ops/ms
Iteration   3: 9.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.655 ±(99.9%) 2.489 ops/ms [Average]
  (min, avg, max) = (9.525, 9.655, 9.797), stdev = 0.136
  CI (99.9%): [7.166, 12.144] (assumes normal distribution)


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
# Warmup Iteration   1: 3.226 ops/ms
# Warmup Iteration   2: 9.161 ops/ms
# Warmup Iteration   3: 9.863 ops/ms
Iteration   1: 9.855 ops/ms
Iteration   2: 9.896 ops/ms
Iteration   3: 10.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.926 ±(99.9%) 1.648 ops/ms [Average]
  (min, avg, max) = (9.855, 9.926, 10.028), stdev = 0.090
  CI (99.9%): [8.278, 11.574] (assumes normal distribution)


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
# Warmup Iteration   1: 3.165 ops/ms
# Warmup Iteration   2: 8.819 ops/ms
# Warmup Iteration   3: 9.628 ops/ms
Iteration   1: 9.791 ops/ms
Iteration   2: 9.585 ops/ms
Iteration   3: 9.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.723 ±(99.9%) 2.179 ops/ms [Average]
  (min, avg, max) = (9.585, 9.723, 9.793), stdev = 0.119
  CI (99.9%): [7.544, 11.902] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.896 ops/ms
# Warmup Iteration   2: 7.040 ops/ms
# Warmup Iteration   3: 7.954 ops/ms
Iteration   1: 8.076 ops/ms
Iteration   2: 8.268 ops/ms
Iteration   3: 8.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.120 ±(99.9%) 2.401 ops/ms [Average]
  (min, avg, max) = (8.016, 8.120, 8.268), stdev = 0.132
  CI (99.9%): [5.719, 10.522] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.245 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.592 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.003 ms/op
Iteration   1: 3.457 ±(99.9%) 0.005 ms/op
Iteration   2: 3.333 ±(99.9%) 0.002 ms/op
Iteration   3: 3.341 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.377 ±(99.9%) 1.267 ms/op [Average]
  (min, avg, max) = (3.333, 3.377, 3.457), stdev = 0.069
  CI (99.9%): [2.110, 4.644] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.067 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.441 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.003 ms/op
Iteration   1: 3.196 ±(99.9%) 0.003 ms/op
Iteration   2: 3.175 ±(99.9%) 0.004 ms/op
Iteration   3: 3.290 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.220 ±(99.9%) 1.117 ms/op [Average]
  (min, avg, max) = (3.175, 3.220, 3.290), stdev = 0.061
  CI (99.9%): [2.103, 4.337] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.483 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.003 ms/op
Iteration   1: 3.332 ±(99.9%) 0.004 ms/op
Iteration   2: 3.309 ±(99.9%) 0.004 ms/op
Iteration   3: 3.313 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.318 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (3.309, 3.318, 3.332), stdev = 0.012
  CI (99.9%): [3.097, 3.539] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.223 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.005 ms/op
Iteration   1: 3.980 ±(99.9%) 0.006 ms/op
Iteration   2: 3.898 ±(99.9%) 0.004 ms/op
Iteration   3: 3.947 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.942 ±(99.9%) 0.754 ms/op [Average]
  (min, avg, max) = (3.898, 3.942, 3.980), stdev = 0.041
  CI (99.9%): [3.188, 4.696] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.236 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.010 ms/op
Iteration   1: 3.353 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  17.711 ms/op
                 createUser·p0.9999: 20.480 ms/op
                 createUser·p1.00:   21.299 ms/op

Iteration   2: 3.342 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.270 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   6.813 ms/op
                 createUser·p0.999:  19.857 ms/op
                 createUser·p0.9999: 22.241 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   3: 3.425 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.956 ms/op
                 createUser·p0.999:  18.358 ms/op
                 createUser·p0.9999: 23.746 ms/op
                 createUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284503
  mean =      3.373 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5604 
    [ 2.500,  5.000) = 269597 
    [ 5.000,  7.500) = 7959 
    [ 7.500, 10.000) = 736 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     18.170 ms/op
     p(99.9900) =     22.628 ms/op
     p(99.9990) =     24.149 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 7.515 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.419 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.180 ±(99.9%) 0.007 ms/op
Iteration   1: 3.332 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   6.250 ms/op
                 existUser·p0.999:  15.478 ms/op
                 existUser·p0.9999: 24.136 ms/op
                 existUser·p1.00:   25.657 ms/op

Iteration   2: 3.338 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   6.742 ms/op
                 existUser·p0.999:  16.457 ms/op
                 existUser·p0.9999: 24.098 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   3: 3.199 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.362 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  16.541 ms/op
                 existUser·p0.9999: 26.903 ms/op
                 existUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291968
  mean =      3.288 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13089 
    [ 2.500,  5.000) = 271602 
    [ 5.000,  7.500) = 6212 
    [ 7.500, 10.000) = 393 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 210 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     15.762 ms/op
     p(99.9900) =     25.350 ms/op
     p(99.9990) =     28.510 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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
# Warmup Iteration   1: 9.647 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.009 ms/op
Iteration   1: 3.372 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  18.741 ms/op
                 getUser·p0.9999: 22.740 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   2: 3.403 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.242 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  20.717 ms/op
                 getUser·p0.9999: 37.737 ms/op
                 getUser·p1.00:   47.645 ms/op

Iteration   3: 3.342 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  17.793 ms/op
                 getUser·p0.9999: 22.930 ms/op
                 getUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284621
  mean =      3.372 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 273721 
    [ 5.000, 10.000) = 10099 
    [10.000, 15.000) = 434 
    [15.000, 20.000) = 161 
    [20.000, 25.000) = 174 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.242 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     18.199 ms/op
     p(99.9900) =     35.818 ms/op
     p(99.9990) =     39.160 ms/op
     p(99.9999) =     47.645 ms/op
    p(100.0000) =     47.645 ms/op


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
# Warmup Iteration   1: 10.026 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.231 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.013 ms/op
Iteration   1: 3.986 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.799 ms/op
                 listUser·p0.999:  18.693 ms/op
                 listUser·p0.9999: 29.287 ms/op
                 listUser·p1.00:   31.621 ms/op

Iteration   2: 3.859 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  15.535 ms/op
                 listUser·p0.9999: 29.955 ms/op
                 listUser·p1.00:   31.261 ms/op

Iteration   3: 3.937 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.968 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.897 ms/op
                 listUser·p0.999:  13.874 ms/op
                 listUser·p0.9999: 19.477 ms/op
                 listUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244302
  mean =      3.927 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 195 
    [ 2.500,  5.000) = 234976 
    [ 5.000,  7.500) = 6060 
    [ 7.500, 10.000) = 2043 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 354 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     15.642 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     31.519 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.655 ± 2.489  ops/ms
ClientPb.existUser                       thrpt       3   9.926 ± 1.648  ops/ms
ClientPb.getUser                         thrpt       3   9.723 ± 2.179  ops/ms
ClientPb.listUser                        thrpt       3   8.120 ± 2.401  ops/ms
ClientPb.createUser                       avgt       3   3.377 ± 1.267   ms/op
ClientPb.existUser                        avgt       3   3.220 ± 1.117   ms/op
ClientPb.getUser                          avgt       3   3.318 ± 0.221   ms/op
ClientPb.listUser                         avgt       3   3.942 ± 0.754   ms/op
ClientPb.createUser                     sample  284503   3.373 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.257           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.734           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.170           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.628           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.395           ms/op
ClientPb.existUser                      sample  291968   3.288 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.169           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.365           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.762           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.350           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.573           ms/op
ClientPb.getUser                        sample  284621   3.372 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.242           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.740           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.701           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.199           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.818           ms/op
ClientPb.getUser:getUser·p1.00          sample          47.645           ms/op
ClientPb.listUser                       sample  244302   3.927 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.104           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.764           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.815           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.642           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.213           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.621           ms/op
