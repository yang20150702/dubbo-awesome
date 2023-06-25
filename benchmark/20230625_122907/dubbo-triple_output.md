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
# Warmup Iteration   1: 2.200 ops/ms
# Warmup Iteration   2: 5.682 ops/ms
# Warmup Iteration   3: 8.658 ops/ms
Iteration   1: 9.318 ops/ms
Iteration   2: 9.208 ops/ms
Iteration   3: 9.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.384 ±(99.9%) 3.954 ops/ms [Average]
  (min, avg, max) = (9.208, 9.384, 9.626), stdev = 0.217
  CI (99.9%): [5.430, 13.338] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.264 ops/ms
# Warmup Iteration   2: 8.777 ops/ms
# Warmup Iteration   3: 9.394 ops/ms
Iteration   1: 9.768 ops/ms
Iteration   2: 9.696 ops/ms
Iteration   3: 9.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.746 ±(99.9%) 0.787 ops/ms [Average]
  (min, avg, max) = (9.696, 9.746, 9.774), stdev = 0.043
  CI (99.9%): [8.959, 10.533] (assumes normal distribution)


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
# Warmup Iteration   1: 2.656 ops/ms
# Warmup Iteration   2: 8.006 ops/ms
# Warmup Iteration   3: 9.007 ops/ms
Iteration   1: 9.186 ops/ms
Iteration   2: 9.347 ops/ms
Iteration   3: 9.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.254 ±(99.9%) 1.522 ops/ms [Average]
  (min, avg, max) = (9.186, 9.254, 9.347), stdev = 0.083
  CI (99.9%): [7.732, 10.776] (assumes normal distribution)


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
# Warmup Iteration   1: 2.923 ops/ms
# Warmup Iteration   2: 7.130 ops/ms
# Warmup Iteration   3: 8.130 ops/ms
Iteration   1: 8.032 ops/ms
Iteration   2: 8.303 ops/ms
Iteration   3: 7.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.108 ±(99.9%) 3.105 ops/ms [Average]
  (min, avg, max) = (7.989, 8.108, 8.303), stdev = 0.170
  CI (99.9%): [5.003, 11.212] (assumes normal distribution)


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
# Warmup Iteration   1: 10.475 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.701 ±(99.9%) 0.005 ms/op
Iteration   1: 3.396 ±(99.9%) 0.014 ms/op
Iteration   2: 3.351 ±(99.9%) 0.016 ms/op
Iteration   3: 3.553 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.433 ±(99.9%) 1.930 ms/op [Average]
  (min, avg, max) = (3.351, 3.433, 3.553), stdev = 0.106
  CI (99.9%): [1.503, 5.364] (assumes normal distribution)


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
# Warmup Iteration   1: 7.443 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.005 ms/op
Iteration   1: 3.242 ±(99.9%) 0.005 ms/op
Iteration   2: 3.344 ±(99.9%) 0.010 ms/op
Iteration   3: 3.228 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.271 ±(99.9%) 1.154 ms/op [Average]
  (min, avg, max) = (3.228, 3.271, 3.344), stdev = 0.063
  CI (99.9%): [2.118, 4.425] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.955 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.002 ms/op
Iteration   1: 3.365 ±(99.9%) 0.010 ms/op
Iteration   2: 3.470 ±(99.9%) 0.002 ms/op
Iteration   3: 3.350 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.395 ±(99.9%) 1.190 ms/op [Average]
  (min, avg, max) = (3.350, 3.395, 3.470), stdev = 0.065
  CI (99.9%): [2.205, 4.585] (assumes normal distribution)


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
# Warmup Iteration   1: 10.392 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.377 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.008 ms/op
Iteration   1: 4.054 ±(99.9%) 0.007 ms/op
Iteration   2: 3.962 ±(99.9%) 0.010 ms/op
Iteration   3: 3.884 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.967 ±(99.9%) 1.548 ms/op [Average]
  (min, avg, max) = (3.884, 3.967, 4.054), stdev = 0.085
  CI (99.9%): [2.419, 5.515] (assumes normal distribution)


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
# Warmup Iteration   1: 9.273 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.009 ms/op
Iteration   1: 3.510 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.620 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   7.143 ms/op
                 createUser·p0.999:  15.560 ms/op
                 createUser·p0.9999: 20.227 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   2: 3.579 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.262 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  17.676 ms/op
                 createUser·p0.9999: 20.094 ms/op
                 createUser·p1.00:   20.644 ms/op

Iteration   3: 3.541 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.551 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  20.120 ms/op
                 createUser·p0.9999: 24.936 ms/op
                 createUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270879
  mean =      3.543 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5849 
    [ 2.500,  5.000) = 255361 
    [ 5.000,  7.500) = 8492 
    [ 7.500, 10.000) = 735 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     24.475 ms/op
     p(99.9990) =     25.227 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 8.029 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.007 ms/op
Iteration   1: 3.412 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   4.026 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  18.195 ms/op
                 existUser·p0.9999: 20.959 ms/op
                 existUser·p1.00:   21.594 ms/op

Iteration   2: 3.395 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.427 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  20.701 ms/op
                 existUser·p0.9999: 29.455 ms/op
                 existUser·p1.00:   30.015 ms/op

Iteration   3: 3.367 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.974 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.972 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  14.959 ms/op
                 existUser·p0.9999: 26.411 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283046
  mean =      3.391 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17566 
    [ 2.500,  5.000) = 259163 
    [ 5.000,  7.500) = 4966 
    [ 7.500, 10.000) = 822 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     14.959 ms/op
     p(99.9900) =     28.032 ms/op
     p(99.9990) =     29.988 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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
# Warmup Iteration   1: 9.043 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.009 ms/op
Iteration   1: 3.615 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   5.554 ms/op
                 getUser·p0.99:   7.250 ms/op
                 getUser·p0.999:  19.399 ms/op
                 getUser·p0.9999: 23.379 ms/op
                 getUser·p1.00:   23.822 ms/op

Iteration   2: 3.464 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.546 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  21.604 ms/op
                 getUser·p0.9999: 27.460 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   3: 3.510 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.630 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.316 ms/op
                 getUser·p0.99:   6.906 ms/op
                 getUser·p0.999:  19.922 ms/op
                 getUser·p0.9999: 41.595 ms/op
                 getUser·p1.00:   43.123 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271793
  mean =      3.529 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 259944 
    [ 5.000, 10.000) = 11321 
    [10.000, 15.000) = 219 
    [15.000, 20.000) = 48 
    [20.000, 25.000) = 174 
    [25.000, 30.000) = 55 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     19.740 ms/op
     p(99.9900) =     40.239 ms/op
     p(99.9990) =     42.813 ms/op
     p(99.9999) =     43.123 ms/op
    p(100.0000) =     43.123 ms/op


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
# Warmup Iteration   1: 10.287 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.474 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.014 ms/op
Iteration   1: 4.062 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.905 ms/op
                 listUser·p0.999:  16.379 ms/op
                 listUser·p0.9999: 23.287 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   2: 4.023 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 19.345 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   3: 4.050 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  16.443 ms/op
                 listUser·p0.9999: 19.038 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237128
  mean =      4.045 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 227788 
    [ 5.000,  7.500) = 6457 
    [ 7.500, 10.000) = 2057 
    [10.000, 12.500) = 236 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.138 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     17.002 ms/op
     p(99.9900) =     22.170 ms/op
     p(99.9990) =     23.851 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.384 ± 3.954  ops/ms
ClientPb.existUser                       thrpt       3   9.746 ± 0.787  ops/ms
ClientPb.getUser                         thrpt       3   9.254 ± 1.522  ops/ms
ClientPb.listUser                        thrpt       3   8.108 ± 3.105  ops/ms
ClientPb.createUser                       avgt       3   3.433 ± 1.930   ms/op
ClientPb.existUser                        avgt       3   3.271 ± 1.154   ms/op
ClientPb.getUser                          avgt       3   3.395 ± 1.190   ms/op
ClientPb.listUser                         avgt       3   3.967 ± 1.548   ms/op
ClientPb.createUser                     sample  270879   3.543 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.551           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.547           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.234           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.007           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.475           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.330           ms/op
ClientPb.existUser                      sample  283046   3.391 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.075           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.046           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.959           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.032           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.015           ms/op
ClientPb.getUser                        sample  271793   3.529 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.697           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.889           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.740           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.239           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.123           ms/op
ClientPb.listUser                       sample  237128   4.045 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.138           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.832           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.002           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.170           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.281           ms/op
