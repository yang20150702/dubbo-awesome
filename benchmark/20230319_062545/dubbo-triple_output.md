# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.143 ops/ms
# Warmup Iteration   2: 2.638 ops/ms
# Warmup Iteration   3: 5.830 ops/ms
Iteration   1: 5.998 ops/ms
Iteration   2: 6.146 ops/ms
Iteration   3: 6.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.132 ±(99.9%) 2.336 ops/ms [Average]
  (min, avg, max) = (5.998, 6.132, 6.253), stdev = 0.128
  CI (99.9%): [3.796, 8.468] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.787 ops/ms
# Warmup Iteration   2: 5.637 ops/ms
# Warmup Iteration   3: 6.524 ops/ms
Iteration   1: 6.502 ops/ms
Iteration   2: 6.479 ops/ms
Iteration   3: 6.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.497 ±(99.9%) 0.284 ops/ms [Average]
  (min, avg, max) = (6.479, 6.497, 6.509), stdev = 0.016
  CI (99.9%): [6.213, 6.780] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.638 ops/ms
# Warmup Iteration   2: 4.452 ops/ms
# Warmup Iteration   3: 6.266 ops/ms
Iteration   1: 5.914 ops/ms
Iteration   2: 5.998 ops/ms
Iteration   3: 6.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.040 ±(99.9%) 2.781 ops/ms [Average]
  (min, avg, max) = (5.914, 6.040, 6.210), stdev = 0.152
  CI (99.9%): [3.259, 8.822] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.486 ops/ms
# Warmup Iteration   2: 4.160 ops/ms
# Warmup Iteration   3: 5.464 ops/ms
Iteration   1: 5.205 ops/ms
Iteration   2: 5.359 ops/ms
Iteration   3: 5.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.358 ±(99.9%) 2.774 ops/ms [Average]
  (min, avg, max) = (5.205, 5.358, 5.510), stdev = 0.152
  CI (99.9%): [2.584, 8.132] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 18.034 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.943 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.345 ±(99.9%) 0.012 ms/op
Iteration   1: 5.121 ±(99.9%) 0.015 ms/op
Iteration   2: 5.161 ±(99.9%) 0.012 ms/op
Iteration   3: 5.281 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.188 ±(99.9%) 1.524 ms/op [Average]
  (min, avg, max) = (5.121, 5.188, 5.281), stdev = 0.084
  CI (99.9%): [3.663, 6.712] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.201 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 6.134 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.208 ±(99.9%) 0.014 ms/op
Iteration   1: 5.009 ±(99.9%) 0.010 ms/op
Iteration   2: 4.911 ±(99.9%) 0.016 ms/op
Iteration   3: 4.905 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.942 ±(99.9%) 1.069 ms/op [Average]
  (min, avg, max) = (4.905, 4.942, 5.009), stdev = 0.059
  CI (99.9%): [3.873, 6.011] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 17.103 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 6.316 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.521 ±(99.9%) 0.010 ms/op
Iteration   1: 5.302 ±(99.9%) 0.014 ms/op
Iteration   2: 5.330 ±(99.9%) 0.008 ms/op
Iteration   3: 5.234 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.289 ±(99.9%) 0.898 ms/op [Average]
  (min, avg, max) = (5.234, 5.289, 5.330), stdev = 0.049
  CI (99.9%): [4.391, 6.186] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.994 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 7.623 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.087 ±(99.9%) 0.016 ms/op
Iteration   1: 6.037 ±(99.9%) 0.010 ms/op
Iteration   2: 6.219 ±(99.9%) 0.012 ms/op
Iteration   3: 6.114 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.123 ±(99.9%) 1.668 ms/op [Average]
  (min, avg, max) = (6.037, 6.123, 6.219), stdev = 0.091
  CI (99.9%): [4.456, 7.791] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.158 ±(99.9%) 0.289 ms/op
# Warmup Iteration   2: 6.918 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.029 ±(99.9%) 0.031 ms/op
Iteration   1: 5.390 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.927 ms/op
                 createUser·p0.50:   5.104 ms/op
                 createUser·p0.90:   6.570 ms/op
                 createUser·p0.95:   7.692 ms/op
                 createUser·p0.99:   10.142 ms/op
                 createUser·p0.999:  23.579 ms/op
                 createUser·p0.9999: 27.460 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   2: 5.308 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.212 ms/op
                 createUser·p0.50:   5.112 ms/op
                 createUser·p0.90:   6.365 ms/op
                 createUser·p0.95:   6.881 ms/op
                 createUser·p0.99:   8.733 ms/op
                 createUser·p0.999:  25.388 ms/op
                 createUser·p0.9999: 28.497 ms/op
                 createUser·p1.00:   29.590 ms/op

Iteration   3: 5.322 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.513 ms/op
                 createUser·p0.50:   5.054 ms/op
                 createUser·p0.90:   6.423 ms/op
                 createUser·p0.95:   7.152 ms/op
                 createUser·p0.99:   10.371 ms/op
                 createUser·p0.999:  25.297 ms/op
                 createUser·p0.9999: 32.604 ms/op
                 createUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 179537
  mean =      5.340 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 80880 
    [ 5.000,  7.500) = 91297 
    [ 7.500, 10.000) = 5685 
    [10.000, 12.500) = 1129 
    [12.500, 15.000) = 316 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.513 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.439 ms/op
     p(95.0000) =      7.184 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     24.263 ms/op
     p(99.9900) =     30.874 ms/op
     p(99.9990) =     32.899 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.366 ±(99.9%) 0.271 ms/op
# Warmup Iteration   2: 5.680 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.286 ±(99.9%) 0.020 ms/op
Iteration   1: 5.152 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.710 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.087 ms/op
                 existUser·p0.95:   7.119 ms/op
                 existUser·p0.99:   10.453 ms/op
                 existUser·p0.999:  22.246 ms/op
                 existUser·p0.9999: 25.283 ms/op
                 existUser·p1.00:   26.477 ms/op

Iteration   2: 5.123 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.367 ms/op
                 existUser·p0.50:   4.833 ms/op
                 existUser·p0.90:   6.152 ms/op
                 existUser·p0.95:   7.168 ms/op
                 existUser·p0.99:   10.617 ms/op
                 existUser·p0.999:  16.810 ms/op
                 existUser·p0.9999: 26.968 ms/op
                 existUser·p1.00:   27.984 ms/op

Iteration   3: 5.080 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.134 ms/op
                 existUser·p0.50:   4.850 ms/op
                 existUser·p0.90:   5.947 ms/op
                 existUser·p0.95:   6.676 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  17.238 ms/op
                 existUser·p0.9999: 27.384 ms/op
                 existUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 187484
  mean =      5.118 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 112345 
    [ 5.000,  7.500) = 67946 
    [ 7.500, 10.000) = 4861 
    [10.000, 12.500) = 1565 
    [12.500, 15.000) = 351 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      1.710 ms/op
     p(50.0000) =      4.858 ms/op
     p(90.0000) =      6.062 ms/op
     p(95.0000) =      6.980 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     17.927 ms/op
     p(99.9900) =     27.075 ms/op
     p(99.9990) =     28.381 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.558 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 6.405 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.464 ±(99.9%) 0.024 ms/op
Iteration   1: 5.367 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.042 ms/op
                 getUser·p0.50:   4.915 ms/op
                 getUser·p0.90:   6.832 ms/op
                 getUser·p0.95:   8.258 ms/op
                 getUser·p0.99:   11.878 ms/op
                 getUser·p0.999:  24.538 ms/op
                 getUser·p0.9999: 31.065 ms/op
                 getUser·p1.00:   31.523 ms/op

Iteration   2: 5.142 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.614 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.078 ms/op
                 getUser·p0.95:   7.250 ms/op
                 getUser·p0.99:   9.961 ms/op
                 getUser·p0.999:  25.900 ms/op
                 getUser·p0.9999: 29.870 ms/op
                 getUser·p1.00:   30.507 ms/op

Iteration   3: 5.294 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.318 ms/op
                 getUser·p0.50:   5.005 ms/op
                 getUser·p0.90:   6.406 ms/op
                 getUser·p0.95:   7.496 ms/op
                 getUser·p0.99:   9.830 ms/op
                 getUser·p0.999:  25.867 ms/op
                 getUser·p0.9999: 30.502 ms/op
                 getUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 182172
  mean =      5.266 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 100152 
    [ 5.000,  7.500) = 71726 
    [ 7.500, 10.000) = 7873 
    [10.000, 12.500) = 1576 
    [12.500, 15.000) = 441 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 96 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      4.923 ms/op
     p(90.0000) =      6.414 ms/op
     p(95.0000) =      7.717 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     24.642 ms/op
     p(99.9900) =     30.533 ms/op
     p(99.9990) =     31.415 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.372 ±(99.9%) 0.340 ms/op
# Warmup Iteration   2: 8.391 ±(99.9%) 0.069 ms/op
# Warmup Iteration   3: 6.334 ±(99.9%) 0.025 ms/op
Iteration   1: 6.255 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.613 ms/op
                 listUser·p0.50:   5.857 ms/op
                 listUser·p0.90:   7.601 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  25.906 ms/op
                 listUser·p0.9999: 28.424 ms/op
                 listUser·p1.00:   29.557 ms/op

Iteration   2: 6.309 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.211 ms/op
                 listUser·p0.50:   5.980 ms/op
                 listUser·p0.90:   7.463 ms/op
                 listUser·p0.95:   8.656 ms/op
                 listUser·p0.99:   12.009 ms/op
                 listUser·p0.999:  28.541 ms/op
                 listUser·p0.9999: 31.446 ms/op
                 listUser·p1.00:   31.687 ms/op

Iteration   3: 6.259 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   5.915 ms/op
                 listUser·p0.90:   7.504 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   11.272 ms/op
                 listUser·p0.999:  22.278 ms/op
                 listUser·p0.9999: 29.062 ms/op
                 listUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152967
  mean =      6.274 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 6499 
    [ 5.000,  7.500) = 130951 
    [ 7.500, 10.000) = 11802 
    [10.000, 12.500) = 2523 
    [12.500, 15.000) = 621 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.527 ms/op
     p(50.0000) =      5.915 ms/op
     p(90.0000) =      7.520 ms/op
     p(95.0000) =      8.815 ms/op
     p(99.0000) =     11.764 ms/op
     p(99.9000) =     26.149 ms/op
     p(99.9900) =     30.081 ms/op
     p(99.9990) =     31.669 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.132 ± 2.336  ops/ms
ClientPb.existUser                       thrpt       3   6.497 ± 0.284  ops/ms
ClientPb.getUser                         thrpt       3   6.040 ± 2.781  ops/ms
ClientPb.listUser                        thrpt       3   5.358 ± 2.774  ops/ms
ClientPb.createUser                       avgt       3   5.188 ± 1.524   ms/op
ClientPb.existUser                        avgt       3   4.942 ± 1.069   ms/op
ClientPb.getUser                          avgt       3   5.289 ± 0.898   ms/op
ClientPb.listUser                         avgt       3   6.123 ± 1.668   ms/op
ClientPb.createUser                     sample  179537   5.340 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.513           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.087           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.439           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.184           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.830           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.263           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.874           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.899           ms/op
ClientPb.existUser                      sample  187484   5.118 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.710           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.858           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.062           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.980           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.453           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.927           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.075           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.410           ms/op
ClientPb.getUser                        sample  182172   5.266 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.614           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.923           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.414           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.717           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.519           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.642           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.533           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.523           ms/op
ClientPb.listUser                       sample  152967   6.274 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.527           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.915           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.520           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.815           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.764           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.149           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.081           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.687           ms/op
