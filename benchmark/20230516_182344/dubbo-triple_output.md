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
# Warmup Iteration   1: 2.121 ops/ms
# Warmup Iteration   2: 5.956 ops/ms
# Warmup Iteration   3: 8.655 ops/ms
Iteration   1: 9.314 ops/ms
Iteration   2: 9.512 ops/ms
Iteration   3: 9.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.350 ±(99.9%) 2.679 ops/ms [Average]
  (min, avg, max) = (9.225, 9.350, 9.512), stdev = 0.147
  CI (99.9%): [6.671, 12.029] (assumes normal distribution)


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
# Warmup Iteration   1: 3.353 ops/ms
# Warmup Iteration   2: 9.179 ops/ms
# Warmup Iteration   3: 9.546 ops/ms
Iteration   1: 9.538 ops/ms
Iteration   2: 10.028 ops/ms
Iteration   3: 9.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.805 ±(99.9%) 4.525 ops/ms [Average]
  (min, avg, max) = (9.538, 9.805, 10.028), stdev = 0.248
  CI (99.9%): [5.281, 14.330] (assumes normal distribution)


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
# Warmup Iteration   1: 2.937 ops/ms
# Warmup Iteration   2: 8.605 ops/ms
# Warmup Iteration   3: 9.345 ops/ms
Iteration   1: 9.163 ops/ms
Iteration   2: 9.446 ops/ms
Iteration   3: 9.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.296 ±(99.9%) 2.596 ops/ms [Average]
  (min, avg, max) = (9.163, 9.296, 9.446), stdev = 0.142
  CI (99.9%): [6.701, 11.892] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.865 ops/ms
# Warmup Iteration   2: 7.013 ops/ms
# Warmup Iteration   3: 7.766 ops/ms
Iteration   1: 7.998 ops/ms
Iteration   2: 8.043 ops/ms
Iteration   3: 8.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.041 ±(99.9%) 0.766 ops/ms [Average]
  (min, avg, max) = (7.998, 8.041, 8.082), stdev = 0.042
  CI (99.9%): [7.275, 8.807] (assumes normal distribution)


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
# Warmup Iteration   1: 8.528 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.007 ms/op
Iteration   1: 3.298 ±(99.9%) 0.009 ms/op
Iteration   2: 3.344 ±(99.9%) 0.006 ms/op
Iteration   3: 3.479 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.374 ±(99.9%) 1.715 ms/op [Average]
  (min, avg, max) = (3.298, 3.374, 3.479), stdev = 0.094
  CI (99.9%): [1.659, 5.088] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.440 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.484 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.009 ms/op
Iteration   1: 3.304 ±(99.9%) 0.010 ms/op
Iteration   2: 3.306 ±(99.9%) 0.011 ms/op
Iteration   3: 3.194 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.268 ±(99.9%) 1.169 ms/op [Average]
  (min, avg, max) = (3.194, 3.268, 3.306), stdev = 0.064
  CI (99.9%): [2.099, 4.437] (assumes normal distribution)


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
# Warmup Iteration   1: 9.621 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.006 ms/op
Iteration   1: 3.501 ±(99.9%) 0.008 ms/op
Iteration   2: 3.449 ±(99.9%) 0.009 ms/op
Iteration   3: 3.356 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.436 ±(99.9%) 1.343 ms/op [Average]
  (min, avg, max) = (3.356, 3.436, 3.501), stdev = 0.074
  CI (99.9%): [2.092, 4.779] (assumes normal distribution)


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
# Warmup Iteration   1: 10.013 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.286 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.008 ms/op
Iteration   1: 4.027 ±(99.9%) 0.007 ms/op
Iteration   2: 3.914 ±(99.9%) 0.014 ms/op
Iteration   3: 3.931 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.958 ±(99.9%) 1.115 ms/op [Average]
  (min, avg, max) = (3.914, 3.958, 4.027), stdev = 0.061
  CI (99.9%): [2.843, 5.072] (assumes normal distribution)


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
# Warmup Iteration   1: 9.453 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.011 ms/op
Iteration   1: 3.383 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.726 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  19.956 ms/op
                 createUser·p0.9999: 22.944 ms/op
                 createUser·p1.00:   24.773 ms/op

Iteration   2: 3.297 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  10.027 ms/op
                 createUser·p0.9999: 25.142 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   3: 3.399 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   6.554 ms/op
                 createUser·p0.999:  17.059 ms/op
                 createUser·p0.9999: 25.723 ms/op
                 createUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285796
  mean =      3.359 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7405 
    [ 2.500,  5.000) = 272043 
    [ 5.000,  7.500) = 5344 
    [ 7.500, 10.000) = 638 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     17.079 ms/op
     p(99.9900) =     25.166 ms/op
     p(99.9990) =     26.299 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 8.439 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.009 ms/op
Iteration   1: 3.283 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  10.528 ms/op
                 existUser·p0.9999: 27.960 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   2: 3.334 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   6.345 ms/op
                 existUser·p0.999:  21.488 ms/op
                 existUser·p0.9999: 25.796 ms/op
                 existUser·p1.00:   28.738 ms/op

Iteration   3: 3.320 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.614 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  15.862 ms/op
                 existUser·p0.9999: 25.428 ms/op
                 existUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289617
  mean =      3.312 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10507 
    [ 2.500,  5.000) = 273974 
    [ 5.000,  7.500) = 3976 
    [ 7.500, 10.000) = 534 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     14.080 ms/op
     p(99.9900) =     26.905 ms/op
     p(99.9990) =     28.755 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 10.635 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.664 ±(99.9%) 0.013 ms/op
Iteration   1: 3.446 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  14.622 ms/op
                 getUser·p0.9999: 22.403 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   2: 3.358 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.442 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  19.464 ms/op
                 getUser·p0.9999: 24.132 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   3: 3.424 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   5.754 ms/op
                 getUser·p0.999:  19.399 ms/op
                 getUser·p0.9999: 33.248 ms/op
                 getUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281765
  mean =      3.409 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3399 
    [ 2.500,  5.000) = 272128 
    [ 5.000,  7.500) = 5193 
    [ 7.500, 10.000) = 611 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     14.746 ms/op
     p(99.9900) =     32.390 ms/op
     p(99.9990) =     33.829 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 9.945 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.455 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.013 ms/op
Iteration   1: 3.958 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  19.012 ms/op
                 listUser·p0.9999: 23.615 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   2: 3.934 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.046 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.766 ms/op
                 listUser·p0.999:  16.199 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   3: 3.898 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  14.237 ms/op
                 listUser·p0.9999: 15.398 ms/op
                 listUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244102
  mean =      3.930 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 235786 
    [ 5.000,  7.500) = 6435 
    [ 7.500, 10.000) = 989 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     15.416 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     24.252 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.350 ± 2.679  ops/ms
ClientPb.existUser                       thrpt       3   9.805 ± 4.525  ops/ms
ClientPb.getUser                         thrpt       3   9.296 ± 2.596  ops/ms
ClientPb.listUser                        thrpt       3   8.041 ± 0.766  ops/ms
ClientPb.createUser                       avgt       3   3.374 ± 1.715   ms/op
ClientPb.existUser                        avgt       3   3.268 ± 1.169   ms/op
ClientPb.getUser                          avgt       3   3.436 ± 1.343   ms/op
ClientPb.listUser                         avgt       3   3.958 ± 1.115   ms/op
ClientPb.createUser                     sample  285796   3.359 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.818           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.080           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.087           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.079           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.166           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.444           ms/op
ClientPb.existUser                      sample  289617   3.312 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.198           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.865           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.080           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.905           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.131           ms/op
ClientPb.getUser                        sample  281765   3.409 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.061           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.939           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.746           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.390           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.406           ms/op
ClientPb.listUser                       sample  244102   3.930 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.581           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.021           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.416           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.086           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.510           ms/op
