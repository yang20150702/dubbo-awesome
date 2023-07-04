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
# Warmup Iteration   1: 2.248 ops/ms
# Warmup Iteration   2: 5.938 ops/ms
# Warmup Iteration   3: 8.330 ops/ms
Iteration   1: 9.121 ops/ms
Iteration   2: 9.471 ops/ms
Iteration   3: 9.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.341 ±(99.9%) 3.498 ops/ms [Average]
  (min, avg, max) = (9.121, 9.341, 9.471), stdev = 0.192
  CI (99.9%): [5.843, 12.840] (assumes normal distribution)


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
# Warmup Iteration   1: 3.203 ops/ms
# Warmup Iteration   2: 8.936 ops/ms
# Warmup Iteration   3: 9.129 ops/ms
Iteration   1: 9.598 ops/ms
Iteration   2: 9.949 ops/ms
Iteration   3: 9.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.702 ±(99.9%) 3.928 ops/ms [Average]
  (min, avg, max) = (9.558, 9.702, 9.949), stdev = 0.215
  CI (99.9%): [5.774, 13.629] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.235 ops/ms
# Warmup Iteration   2: 8.703 ops/ms
# Warmup Iteration   3: 9.008 ops/ms
Iteration   1: 9.277 ops/ms
Iteration   2: 9.273 ops/ms
Iteration   3: 9.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.283 ±(99.9%) 0.255 ops/ms [Average]
  (min, avg, max) = (9.273, 9.283, 9.299), stdev = 0.014
  CI (99.9%): [9.029, 9.538] (assumes normal distribution)


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
# Warmup Iteration   1: 2.467 ops/ms
# Warmup Iteration   2: 6.978 ops/ms
# Warmup Iteration   3: 7.602 ops/ms
Iteration   1: 7.850 ops/ms
Iteration   2: 7.954 ops/ms
Iteration   3: 7.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.924 ±(99.9%) 1.174 ops/ms [Average]
  (min, avg, max) = (7.850, 7.924, 7.968), stdev = 0.064
  CI (99.9%): [6.750, 9.098] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.623 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.004 ms/op
Iteration   1: 3.408 ±(99.9%) 0.007 ms/op
Iteration   2: 3.600 ±(99.9%) 0.009 ms/op
Iteration   3: 3.575 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.528 ±(99.9%) 1.904 ms/op [Average]
  (min, avg, max) = (3.408, 3.528, 3.600), stdev = 0.104
  CI (99.9%): [1.624, 5.431] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.930 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.008 ms/op
Iteration   1: 3.381 ±(99.9%) 0.004 ms/op
Iteration   2: 3.211 ±(99.9%) 0.011 ms/op
Iteration   3: 3.278 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.290 ±(99.9%) 1.566 ms/op [Average]
  (min, avg, max) = (3.211, 3.290, 3.381), stdev = 0.086
  CI (99.9%): [1.724, 4.856] (assumes normal distribution)


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
# Warmup Iteration   1: 9.796 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.544 ±(99.9%) 0.009 ms/op
Iteration   1: 3.486 ±(99.9%) 0.003 ms/op
Iteration   2: 3.476 ±(99.9%) 0.009 ms/op
Iteration   3: 3.471 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.478 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (3.471, 3.478, 3.486), stdev = 0.008
  CI (99.9%): [3.339, 3.617] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.798 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.008 ms/op
Iteration   1: 4.091 ±(99.9%) 0.009 ms/op
Iteration   2: 3.996 ±(99.9%) 0.009 ms/op
Iteration   3: 3.972 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.020 ±(99.9%) 1.149 ms/op [Average]
  (min, avg, max) = (3.972, 4.020, 4.091), stdev = 0.063
  CI (99.9%): [2.871, 5.169] (assumes normal distribution)


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
# Warmup Iteration   1: 10.845 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.629 ±(99.9%) 0.013 ms/op
Iteration   1: 3.457 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.649 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  22.348 ms/op
                 createUser·p0.9999: 44.630 ms/op
                 createUser·p1.00:   45.875 ms/op

Iteration   2: 3.369 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.733 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  23.075 ms/op
                 createUser·p0.9999: 27.886 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   3: 3.547 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.692 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  18.310 ms/op
                 createUser·p0.9999: 27.328 ms/op
                 createUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277707
  mean =      3.456 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 267667 
    [ 5.000, 10.000) = 9641 
    [10.000, 15.000) = 47 
    [15.000, 20.000) = 81 
    [20.000, 25.000) = 134 
    [25.000, 30.000) = 126 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.649 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     19.713 ms/op
     p(99.9900) =     27.729 ms/op
     p(99.9990) =     45.577 ms/op
     p(99.9999) =     45.875 ms/op
    p(100.0000) =     45.875 ms/op


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
# Warmup Iteration   1: 9.271 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.008 ms/op
Iteration   1: 3.306 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.491 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  13.836 ms/op
                 existUser·p0.9999: 25.864 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   2: 3.414 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  22.490 ms/op
                 existUser·p0.9999: 27.742 ms/op
                 existUser·p1.00:   27.886 ms/op

Iteration   3: 3.362 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.501 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  23.839 ms/op
                 existUser·p0.9999: 28.259 ms/op
                 existUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285580
  mean =      3.360 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15078 
    [ 2.500,  5.000) = 264493 
    [ 5.000,  7.500) = 5025 
    [ 7.500, 10.000) = 447 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 142 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     21.692 ms/op
     p(99.9900) =     27.722 ms/op
     p(99.9990) =     30.287 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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
# Warmup Iteration   1: 9.226 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.010 ms/op
Iteration   1: 3.481 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.487 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.400 ms/op
                 getUser·p0.999:  21.238 ms/op
                 getUser·p0.9999: 25.195 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   2: 3.421 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   6.196 ms/op
                 getUser·p0.999:  23.873 ms/op
                 getUser·p0.9999: 29.447 ms/op
                 getUser·p1.00:   29.819 ms/op

Iteration   3: 3.504 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  19.484 ms/op
                 getUser·p0.9999: 25.915 ms/op
                 getUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276670
  mean =      3.469 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9717 
    [ 2.500,  5.000) = 258662 
    [ 5.000,  7.500) = 7111 
    [ 7.500, 10.000) = 643 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     19.912 ms/op
     p(99.9900) =     28.748 ms/op
     p(99.9990) =     29.736 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 11.278 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.409 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.204 ±(99.9%) 0.014 ms/op
Iteration   1: 4.086 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.009 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  26.367 ms/op
                 listUser·p0.9999: 32.850 ms/op
                 listUser·p1.00:   34.734 ms/op

Iteration   2: 4.064 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 21.996 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   3: 3.983 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.320 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 22.512 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237293
  mean =      4.044 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 229383 
    [ 5.000,  7.500) = 5678 
    [ 7.500, 10.000) = 1296 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     32.008 ms/op
     p(99.9990) =     33.419 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.341 ± 3.498  ops/ms
ClientPb.existUser                       thrpt       3   9.702 ± 3.928  ops/ms
ClientPb.getUser                         thrpt       3   9.283 ± 0.255  ops/ms
ClientPb.listUser                        thrpt       3   7.924 ± 1.174  ops/ms
ClientPb.createUser                       avgt       3   3.528 ± 1.904   ms/op
ClientPb.existUser                        avgt       3   3.290 ± 1.566   ms/op
ClientPb.getUser                          avgt       3   3.478 ± 0.139   ms/op
ClientPb.listUser                         avgt       3   4.020 ± 1.149   ms/op
ClientPb.createUser                     sample  277707   3.456 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.649           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.432           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.226           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.713           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.729           ms/op
ClientPb.createUser:createUser·p1.00    sample          45.875           ms/op
ClientPb.existUser                      sample  285580   3.360 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.491           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.692           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.722           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.343           ms/op
ClientPb.getUser                        sample  276670   3.469 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.339           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.332           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.912           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.748           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.819           ms/op
ClientPb.listUser                       sample  237293   4.044 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.614           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.406           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.547           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.008           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.734           ms/op
