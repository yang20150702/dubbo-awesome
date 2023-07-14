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
# Warmup Iteration   1: 2.258 ops/ms
# Warmup Iteration   2: 6.241 ops/ms
# Warmup Iteration   3: 8.963 ops/ms
Iteration   1: 9.732 ops/ms
Iteration   2: 9.221 ops/ms
Iteration   3: 9.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.496 ±(99.9%) 4.699 ops/ms [Average]
  (min, avg, max) = (9.221, 9.496, 9.732), stdev = 0.258
  CI (99.9%): [4.797, 14.194] (assumes normal distribution)


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
# Warmup Iteration   1: 3.323 ops/ms
# Warmup Iteration   2: 9.319 ops/ms
# Warmup Iteration   3: 9.468 ops/ms
Iteration   1: 9.766 ops/ms
Iteration   2: 10.187 ops/ms
Iteration   3: 9.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.909 ±(99.9%) 4.392 ops/ms [Average]
  (min, avg, max) = (9.766, 9.909, 10.187), stdev = 0.241
  CI (99.9%): [5.518, 14.301] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.149 ops/ms
# Warmup Iteration   2: 8.651 ops/ms
# Warmup Iteration   3: 9.192 ops/ms
Iteration   1: 9.392 ops/ms
Iteration   2: 9.495 ops/ms
Iteration   3: 9.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.411 ±(99.9%) 1.385 ops/ms [Average]
  (min, avg, max) = (9.346, 9.411, 9.495), stdev = 0.076
  CI (99.9%): [8.026, 10.796] (assumes normal distribution)


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
# Warmup Iteration   1: 3.083 ops/ms
# Warmup Iteration   2: 7.475 ops/ms
# Warmup Iteration   3: 7.889 ops/ms
Iteration   1: 8.440 ops/ms
Iteration   2: 8.131 ops/ms
Iteration   3: 8.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.242 ±(99.9%) 3.128 ops/ms [Average]
  (min, avg, max) = (8.131, 8.242, 8.440), stdev = 0.171
  CI (99.9%): [5.114, 11.370] (assumes normal distribution)


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
# Warmup Iteration   1: 9.435 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.598 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.008 ms/op
Iteration   1: 3.249 ±(99.9%) 0.009 ms/op
Iteration   2: 3.357 ±(99.9%) 0.008 ms/op
Iteration   3: 3.285 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.297 ±(99.9%) 1.006 ms/op [Average]
  (min, avg, max) = (3.249, 3.297, 3.357), stdev = 0.055
  CI (99.9%): [2.291, 4.303] (assumes normal distribution)


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
# Warmup Iteration   1: 8.579 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.005 ms/op
Iteration   1: 3.393 ±(99.9%) 0.002 ms/op
Iteration   2: 3.218 ±(99.9%) 0.005 ms/op
Iteration   3: 3.143 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.251 ±(99.9%) 2.344 ms/op [Average]
  (min, avg, max) = (3.143, 3.251, 3.393), stdev = 0.128
  CI (99.9%): [0.907, 5.596] (assumes normal distribution)


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
# Warmup Iteration   1: 7.681 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.779 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.006 ms/op
Iteration   1: 3.370 ±(99.9%) 0.005 ms/op
Iteration   2: 3.307 ±(99.9%) 0.010 ms/op
Iteration   3: 3.361 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.346 ±(99.9%) 0.623 ms/op [Average]
  (min, avg, max) = (3.307, 3.346, 3.370), stdev = 0.034
  CI (99.9%): [2.723, 3.969] (assumes normal distribution)


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
# Warmup Iteration   1: 10.721 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.346 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.010 ms/op
Iteration   1: 3.865 ±(99.9%) 0.013 ms/op
Iteration   2: 3.902 ±(99.9%) 0.010 ms/op
Iteration   3: 3.849 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.872 ±(99.9%) 0.499 ms/op [Average]
  (min, avg, max) = (3.849, 3.872, 3.902), stdev = 0.027
  CI (99.9%): [3.373, 4.371] (assumes normal distribution)


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
# Warmup Iteration   1: 8.787 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.035 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.009 ms/op
Iteration   1: 3.307 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.786 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.551 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  15.899 ms/op
                 createUser·p0.9999: 21.966 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   2: 3.375 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  20.748 ms/op
                 createUser·p0.9999: 22.758 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   3: 3.417 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.567 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   5.674 ms/op
                 createUser·p0.999:  16.130 ms/op
                 createUser·p0.9999: 24.859 ms/op
                 createUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284990
  mean =      3.366 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19132 
    [ 2.500,  5.000) = 260923 
    [ 5.000,  7.500) = 3989 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 188 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     18.743 ms/op
     p(99.9900) =     23.773 ms/op
     p(99.9990) =     24.904 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 8.034 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.009 ms/op
Iteration   1: 3.332 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.653 ms/op
                 existUser·p0.999:  20.513 ms/op
                 existUser·p0.9999: 34.039 ms/op
                 existUser·p1.00:   35.455 ms/op

Iteration   2: 3.400 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  21.820 ms/op
                 existUser·p0.9999: 25.710 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   3: 3.337 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  19.694 ms/op
                 existUser·p0.9999: 31.919 ms/op
                 existUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285856
  mean =      3.356 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7192 
    [ 2.500,  5.000) = 272707 
    [ 5.000,  7.500) = 4957 
    [ 7.500, 10.000) = 663 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     19.787 ms/op
     p(99.9900) =     31.405 ms/op
     p(99.9990) =     35.202 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


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
# Warmup Iteration   1: 8.352 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.011 ms/op
Iteration   1: 3.390 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  12.026 ms/op
                 getUser·p0.9999: 28.363 ms/op
                 getUser·p1.00:   31.326 ms/op

Iteration   2: 3.407 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.460 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  21.401 ms/op
                 getUser·p0.9999: 30.999 ms/op
                 getUser·p1.00:   31.752 ms/op

Iteration   3: 3.405 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.346 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  17.007 ms/op
                 getUser·p0.9999: 27.840 ms/op
                 getUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282131
  mean =      3.401 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7511 
    [ 2.500,  5.000) = 268495 
    [ 5.000,  7.500) = 5215 
    [ 7.500, 10.000) = 465 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     14.615 ms/op
     p(99.9900) =     30.231 ms/op
     p(99.9990) =     31.621 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 10.182 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.291 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.010 ms/op
Iteration   1: 3.885 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.780 ms/op
                 listUser·p0.999:  16.919 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   2: 3.954 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.665 ms/op
                 listUser·p0.999:  15.554 ms/op
                 listUser·p0.9999: 18.416 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   3: 3.894 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.040 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.010 ms/op
                 listUser·p0.999:  13.926 ms/op
                 listUser·p0.9999: 15.516 ms/op
                 listUser·p1.00:   15.581 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245409
  mean =      3.911 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 238023 
    [ 5.000,  7.500) = 5307 
    [ 7.500, 10.000) = 1216 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 290 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.987 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     15.106 ms/op
     p(99.9900) =     19.131 ms/op
     p(99.9990) =     21.433 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.496 ± 4.699  ops/ms
ClientPb.existUser                       thrpt       3   9.909 ± 4.392  ops/ms
ClientPb.getUser                         thrpt       3   9.411 ± 1.385  ops/ms
ClientPb.listUser                        thrpt       3   8.242 ± 3.128  ops/ms
ClientPb.createUser                       avgt       3   3.297 ± 1.006   ms/op
ClientPb.existUser                        avgt       3   3.251 ± 2.344   ms/op
ClientPb.getUser                          avgt       3   3.346 ± 0.623   ms/op
ClientPb.listUser                         avgt       3   3.872 ± 0.499   ms/op
ClientPb.createUser                     sample  284990   3.366 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.567           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.743           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.773           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.492           ms/op
ClientPb.existUser                      sample  285856   3.356 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.063           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.309           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.787           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.405           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.455           ms/op
ClientPb.getUser                        sample  282131   3.401 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.346           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.615           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.231           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.752           ms/op
ClientPb.listUser                       sample  245409   3.911 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.987           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.768           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.160           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.106           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.131           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.496           ms/op
