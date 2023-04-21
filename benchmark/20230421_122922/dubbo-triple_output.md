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
# Warmup Iteration   1: 1.085 ops/ms
# Warmup Iteration   2: 2.097 ops/ms
# Warmup Iteration   3: 4.874 ops/ms
Iteration   1: 5.476 ops/ms
Iteration   2: 5.540 ops/ms
Iteration   3: 5.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.639 ±(99.9%) 4.185 ops/ms [Average]
  (min, avg, max) = (5.476, 5.639, 5.902), stdev = 0.229
  CI (99.9%): [1.454, 9.824] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.478 ops/ms
# Warmup Iteration   2: 4.273 ops/ms
# Warmup Iteration   3: 6.092 ops/ms
Iteration   1: 5.901 ops/ms
Iteration   2: 5.959 ops/ms
Iteration   3: 6.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.021 ±(99.9%) 2.912 ops/ms [Average]
  (min, avg, max) = (5.901, 6.021, 6.202), stdev = 0.160
  CI (99.9%): [3.109, 8.932] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.440 ops/ms
# Warmup Iteration   2: 4.208 ops/ms
# Warmup Iteration   3: 5.600 ops/ms
Iteration   1: 5.598 ops/ms
Iteration   2: 5.740 ops/ms
Iteration   3: 5.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.732 ±(99.9%) 2.383 ops/ms [Average]
  (min, avg, max) = (5.598, 5.732, 5.859), stdev = 0.131
  CI (99.9%): [3.349, 8.115] (assumes normal distribution)


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
# Warmup Iteration   1: 1.438 ops/ms
# Warmup Iteration   2: 4.216 ops/ms
# Warmup Iteration   3: 4.820 ops/ms
Iteration   1: 5.143 ops/ms
Iteration   2: 5.151 ops/ms
Iteration   3: 5.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.120 ±(99.9%) 0.848 ops/ms [Average]
  (min, avg, max) = (5.067, 5.120, 5.151), stdev = 0.046
  CI (99.9%): [4.272, 5.968] (assumes normal distribution)


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
# Warmup Iteration   1: 19.291 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 6.306 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.466 ±(99.9%) 0.011 ms/op
Iteration   1: 5.406 ±(99.9%) 0.008 ms/op
Iteration   2: 5.549 ±(99.9%) 0.011 ms/op
Iteration   3: 5.170 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.375 ±(99.9%) 3.495 ms/op [Average]
  (min, avg, max) = (5.170, 5.375, 5.549), stdev = 0.192
  CI (99.9%): [1.880, 8.870] (assumes normal distribution)


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
# Warmup Iteration   1: 16.244 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.605 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.282 ±(99.9%) 0.009 ms/op
Iteration   1: 5.133 ±(99.9%) 0.008 ms/op
Iteration   2: 5.123 ±(99.9%) 0.013 ms/op
Iteration   3: 5.243 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.167 ±(99.9%) 1.218 ms/op [Average]
  (min, avg, max) = (5.123, 5.167, 5.243), stdev = 0.067
  CI (99.9%): [3.948, 6.385] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 17.749 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 6.999 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.648 ±(99.9%) 0.013 ms/op
Iteration   1: 5.549 ±(99.9%) 0.009 ms/op
Iteration   2: 5.352 ±(99.9%) 0.013 ms/op
Iteration   3: 5.173 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.358 ±(99.9%) 3.430 ms/op [Average]
  (min, avg, max) = (5.173, 5.358, 5.549), stdev = 0.188
  CI (99.9%): [1.928, 8.788] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 20.068 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 7.301 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.318 ±(99.9%) 0.017 ms/op
Iteration   1: 6.338 ±(99.9%) 0.012 ms/op
Iteration   2: 6.037 ±(99.9%) 0.017 ms/op
Iteration   3: 6.165 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.180 ±(99.9%) 2.758 ms/op [Average]
  (min, avg, max) = (6.037, 6.180, 6.338), stdev = 0.151
  CI (99.9%): [3.421, 8.938] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 17.872 ±(99.9%) 0.283 ms/op
# Warmup Iteration   2: 6.251 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.582 ±(99.9%) 0.029 ms/op
Iteration   1: 5.445 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   5.022 ms/op
                 createUser·p0.90:   7.094 ms/op
                 createUser·p0.95:   8.225 ms/op
                 createUser·p0.99:   11.320 ms/op
                 createUser·p0.999:  23.795 ms/op
                 createUser·p0.9999: 27.656 ms/op
                 createUser·p1.00:   27.820 ms/op

Iteration   2: 5.506 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.327 ms/op
                 createUser·p0.50:   5.186 ms/op
                 createUser·p0.90:   6.898 ms/op
                 createUser·p0.95:   7.930 ms/op
                 createUser·p0.99:   10.813 ms/op
                 createUser·p0.999:  24.476 ms/op
                 createUser·p0.9999: 28.646 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   3: 5.441 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.359 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   6.832 ms/op
                 createUser·p0.95:   7.840 ms/op
                 createUser·p0.99:   10.254 ms/op
                 createUser·p0.999:  26.448 ms/op
                 createUser·p0.9999: 29.688 ms/op
                 createUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175583
  mean =      5.464 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 78042 
    [ 5.000,  7.500) = 84905 
    [ 7.500, 10.000) = 9802 
    [10.000, 12.500) = 1925 
    [12.500, 15.000) = 507 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      6.947 ms/op
     p(95.0000) =      8.004 ms/op
     p(99.0000) =     10.846 ms/op
     p(99.9000) =     24.052 ms/op
     p(99.9900) =     29.000 ms/op
     p(99.9990) =     30.298 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 16.747 ±(99.9%) 0.255 ms/op
# Warmup Iteration   2: 6.002 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.319 ±(99.9%) 0.019 ms/op
Iteration   1: 5.163 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   4.776 ms/op
                 existUser·p0.90:   6.513 ms/op
                 existUser·p0.95:   7.414 ms/op
                 existUser·p0.99:   9.945 ms/op
                 existUser·p0.999:  26.511 ms/op
                 existUser·p0.9999: 31.373 ms/op
                 existUser·p1.00:   31.621 ms/op

Iteration   2: 5.204 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.023 ms/op
                 existUser·p0.50:   4.825 ms/op
                 existUser·p0.90:   6.636 ms/op
                 existUser·p0.95:   7.586 ms/op
                 existUser·p0.99:   10.273 ms/op
                 existUser·p0.999:  16.581 ms/op
                 existUser·p0.9999: 27.291 ms/op
                 existUser·p1.00:   28.803 ms/op

Iteration   3: 5.293 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   4.907 ms/op
                 existUser·p0.90:   6.595 ms/op
                 existUser·p0.95:   7.512 ms/op
                 existUser·p0.99:   11.338 ms/op
                 existUser·p0.999:  29.007 ms/op
                 existUser·p0.9999: 35.112 ms/op
                 existUser·p1.00:   37.093 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 183744
  mean =      5.219 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 107566 
    [ 5.000,  7.500) = 66865 
    [ 7.500, 10.000) = 6939 
    [10.000, 12.500) = 1454 
    [12.500, 15.000) = 556 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.586 ms/op
     p(95.0000) =      7.512 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     17.965 ms/op
     p(99.9900) =     33.554 ms/op
     p(99.9990) =     35.996 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.968 ±(99.9%) 0.285 ms/op
# Warmup Iteration   2: 6.535 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.450 ±(99.9%) 0.020 ms/op
Iteration   1: 5.398 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.087 ms/op
                 getUser·p0.50:   4.923 ms/op
                 getUser·p0.90:   6.857 ms/op
                 getUser·p0.95:   8.380 ms/op
                 getUser·p0.99:   12.630 ms/op
                 getUser·p0.999:  25.362 ms/op
                 getUser·p0.9999: 27.331 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   2: 5.385 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.504 ms/op
                 getUser·p0.50:   5.030 ms/op
                 getUser·p0.90:   6.717 ms/op
                 getUser·p0.95:   7.717 ms/op
                 getUser·p0.99:   10.633 ms/op
                 getUser·p0.999:  24.777 ms/op
                 getUser·p0.9999: 28.481 ms/op
                 getUser·p1.00:   30.573 ms/op

Iteration   3: 5.447 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.343 ms/op
                 getUser·p0.50:   5.030 ms/op
                 getUser·p0.90:   6.980 ms/op
                 getUser·p0.95:   8.020 ms/op
                 getUser·p0.99:   10.930 ms/op
                 getUser·p0.999:  17.891 ms/op
                 getUser·p0.9999: 29.758 ms/op
                 getUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177438
  mean =      5.410 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 89625 
    [ 5.000,  7.500) = 75727 
    [ 7.500, 10.000) = 8692 
    [10.000, 12.500) = 2109 
    [12.500, 15.000) = 763 
    [15.000, 17.500) = 223 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 127 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      6.840 ms/op
     p(95.0000) =      8.020 ms/op
     p(99.0000) =     11.616 ms/op
     p(99.9000) =     24.496 ms/op
     p(99.9900) =     28.305 ms/op
     p(99.9990) =     30.319 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.537 ±(99.9%) 0.325 ms/op
# Warmup Iteration   2: 7.684 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.282 ±(99.9%) 0.027 ms/op
Iteration   1: 6.157 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   5.743 ms/op
                 listUser·p0.90:   7.840 ms/op
                 listUser·p0.95:   8.864 ms/op
                 listUser·p0.99:   11.583 ms/op
                 listUser·p0.999:  27.361 ms/op
                 listUser·p0.9999: 30.468 ms/op
                 listUser·p1.00:   30.966 ms/op

Iteration   2: 6.112 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.535 ms/op
                 listUser·p0.50:   5.726 ms/op
                 listUser·p0.90:   7.643 ms/op
                 listUser·p0.95:   8.765 ms/op
                 listUser·p0.99:   11.551 ms/op
                 listUser·p0.999:  29.884 ms/op
                 listUser·p0.9999: 31.901 ms/op
                 listUser·p1.00:   33.227 ms/op

Iteration   3: 6.137 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.994 ms/op
                 listUser·p0.50:   5.800 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   12.075 ms/op
                 listUser·p0.999:  20.316 ms/op
                 listUser·p0.9999: 23.914 ms/op
                 listUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 156392
  mean =      6.136 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 15144 
    [ 5.000,  7.500) = 124366 
    [ 7.500, 10.000) = 13414 
    [10.000, 12.500) = 2253 
    [12.500, 15.000) = 681 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      5.759 ms/op
     p(90.0000) =      7.627 ms/op
     p(95.0000) =      8.716 ms/op
     p(99.0000) =     11.747 ms/op
     p(99.9000) =     26.726 ms/op
     p(99.9900) =     31.469 ms/op
     p(99.9990) =     32.709 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.639 ± 4.185  ops/ms
ClientPb.existUser                       thrpt       3   6.021 ± 2.912  ops/ms
ClientPb.getUser                         thrpt       3   5.732 ± 2.383  ops/ms
ClientPb.listUser                        thrpt       3   5.120 ± 0.848  ops/ms
ClientPb.createUser                       avgt       3   5.375 ± 3.495   ms/op
ClientPb.existUser                        avgt       3   5.167 ± 1.218   ms/op
ClientPb.getUser                          avgt       3   5.358 ± 3.430   ms/op
ClientPb.listUser                         avgt       3   6.180 ± 2.758   ms/op
ClientPb.createUser                     sample  175583   5.464 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.253           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.120           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.947           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.004           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.846           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.052           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.000           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.867           ms/op
ClientPb.existUser                      sample  183744   5.219 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.825           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.833           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.586           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.512           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.617           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.965           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.554           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.093           ms/op
ClientPb.getUser                        sample  177438   5.410 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.504           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.989           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.840           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.020           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.616           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.496           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.305           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.573           ms/op
ClientPb.listUser                       sample  156392   6.136 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.397           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.759           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.627           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.716           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.747           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.726           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.469           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.227           ms/op
