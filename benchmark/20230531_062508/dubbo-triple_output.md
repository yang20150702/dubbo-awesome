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
# Warmup Iteration   1: 0.911 ops/ms
# Warmup Iteration   2: 1.991 ops/ms
# Warmup Iteration   3: 4.396 ops/ms
Iteration   1: 5.254 ops/ms
Iteration   2: 5.585 ops/ms
Iteration   3: 5.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.384 ±(99.9%) 3.213 ops/ms [Average]
  (min, avg, max) = (5.254, 5.384, 5.585), stdev = 0.176
  CI (99.9%): [2.171, 8.597] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.443 ops/ms
# Warmup Iteration   2: 4.162 ops/ms
# Warmup Iteration   3: 5.566 ops/ms
Iteration   1: 5.791 ops/ms
Iteration   2: 5.751 ops/ms
Iteration   3: 5.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.775 ±(99.9%) 0.376 ops/ms [Average]
  (min, avg, max) = (5.751, 5.775, 5.791), stdev = 0.021
  CI (99.9%): [5.399, 6.150] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.217 ops/ms
# Warmup Iteration   2: 3.437 ops/ms
# Warmup Iteration   3: 5.119 ops/ms
Iteration   1: 5.447 ops/ms
Iteration   2: 5.267 ops/ms
Iteration   3: 5.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.330 ±(99.9%) 1.841 ops/ms [Average]
  (min, avg, max) = (5.267, 5.330, 5.447), stdev = 0.101
  CI (99.9%): [3.490, 7.171] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.248 ops/ms
# Warmup Iteration   2: 3.849 ops/ms
# Warmup Iteration   3: 4.556 ops/ms
Iteration   1: 4.639 ops/ms
Iteration   2: 4.668 ops/ms
Iteration   3: 4.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.684 ±(99.9%) 1.015 ops/ms [Average]
  (min, avg, max) = (4.639, 4.684, 4.746), stdev = 0.056
  CI (99.9%): [3.669, 5.699] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 19.340 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 7.558 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.944 ±(99.9%) 0.016 ms/op
Iteration   1: 5.843 ±(99.9%) 0.021 ms/op
Iteration   2: 5.903 ±(99.9%) 0.012 ms/op
Iteration   3: 5.656 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.801 ±(99.9%) 2.350 ms/op [Average]
  (min, avg, max) = (5.656, 5.801, 5.903), stdev = 0.129
  CI (99.9%): [3.451, 8.151] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 20.798 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 7.060 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.616 ±(99.9%) 0.011 ms/op
Iteration   1: 5.485 ±(99.9%) 0.013 ms/op
Iteration   2: 5.343 ±(99.9%) 0.016 ms/op
Iteration   3: 5.378 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.402 ±(99.9%) 1.351 ms/op [Average]
  (min, avg, max) = (5.343, 5.402, 5.485), stdev = 0.074
  CI (99.9%): [4.052, 6.753] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.982 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 7.015 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.893 ±(99.9%) 0.017 ms/op
Iteration   1: 5.821 ±(99.9%) 0.014 ms/op
Iteration   2: 5.946 ±(99.9%) 0.009 ms/op
Iteration   3: 5.582 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.783 ±(99.9%) 3.372 ms/op [Average]
  (min, avg, max) = (5.582, 5.783, 5.946), stdev = 0.185
  CI (99.9%): [2.411, 9.155] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 21.442 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 8.872 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.840 ±(99.9%) 0.017 ms/op
Iteration   1: 6.842 ±(99.9%) 0.023 ms/op
Iteration   2: 6.684 ±(99.9%) 0.022 ms/op
Iteration   3: 6.523 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.683 ±(99.9%) 2.916 ms/op [Average]
  (min, avg, max) = (6.523, 6.683, 6.842), stdev = 0.160
  CI (99.9%): [3.767, 9.599] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.741 ±(99.9%) 0.312 ms/op
# Warmup Iteration   2: 7.767 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.324 ±(99.9%) 0.030 ms/op
Iteration   1: 5.861 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.021 ms/op
                 createUser·p0.50:   5.587 ms/op
                 createUser·p0.90:   7.242 ms/op
                 createUser·p0.95:   8.421 ms/op
                 createUser·p0.99:   10.912 ms/op
                 createUser·p0.999:  14.483 ms/op
                 createUser·p0.9999: 26.348 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   2: 5.602 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.720 ms/op
                 createUser·p0.50:   5.308 ms/op
                 createUser·p0.90:   6.791 ms/op
                 createUser·p0.95:   7.848 ms/op
                 createUser·p0.99:   10.273 ms/op
                 createUser·p0.999:  27.457 ms/op
                 createUser·p0.9999: 30.451 ms/op
                 createUser·p1.00:   30.835 ms/op

Iteration   3: 5.745 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.429 ms/op
                 createUser·p0.50:   5.530 ms/op
                 createUser·p0.90:   6.889 ms/op
                 createUser·p0.95:   7.569 ms/op
                 createUser·p0.99:   10.289 ms/op
                 createUser·p0.999:  30.125 ms/op
                 createUser·p0.9999: 47.346 ms/op
                 createUser·p1.00:   49.086 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 167304
  mean =      5.734 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 41170 
    [ 5.000, 10.000) = 123743 
    [10.000, 15.000) = 2189 
    [15.000, 20.000) = 42 
    [20.000, 25.000) = 15 
    [25.000, 30.000) = 68 
    [30.000, 35.000) = 45 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.021 ms/op
     p(50.0000) =      5.456 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      7.954 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     16.397 ms/op
     p(99.9900) =     45.875 ms/op
     p(99.9990) =     48.998 ms/op
     p(99.9999) =     49.086 ms/op
    p(100.0000) =     49.086 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.653 ±(99.9%) 0.290 ms/op
# Warmup Iteration   2: 6.205 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.339 ±(99.9%) 0.018 ms/op
Iteration   1: 5.539 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.628 ms/op
                 existUser·p0.50:   5.210 ms/op
                 existUser·p0.90:   6.857 ms/op
                 existUser·p0.95:   7.889 ms/op
                 existUser·p0.99:   10.617 ms/op
                 existUser·p0.999:  26.757 ms/op
                 existUser·p0.9999: 29.557 ms/op
                 existUser·p1.00:   33.882 ms/op

Iteration   2: 5.288 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.335 ms/op
                 existUser·p0.50:   5.063 ms/op
                 existUser·p0.90:   6.291 ms/op
                 existUser·p0.95:   7.119 ms/op
                 existUser·p0.99:   9.634 ms/op
                 existUser·p0.999:  12.886 ms/op
                 existUser·p0.9999: 29.775 ms/op
                 existUser·p1.00:   30.736 ms/op

Iteration   3: 5.498 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.515 ms/op
                 existUser·p0.50:   5.226 ms/op
                 existUser·p0.90:   6.562 ms/op
                 existUser·p0.95:   7.586 ms/op
                 existUser·p0.99:   10.304 ms/op
                 existUser·p0.999:  27.623 ms/op
                 existUser·p0.9999: 60.948 ms/op
                 existUser·p1.00:   61.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176405
  mean =      5.439 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 69943 
    [ 5.000, 10.000) = 104324 
    [10.000, 15.000) = 1839 
    [15.000, 20.000) = 86 
    [20.000, 25.000) = 30 
    [25.000, 30.000) = 130 
    [30.000, 35.000) = 21 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 13 
    [60.000, 65.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.628 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      6.578 ms/op
     p(95.0000) =      7.569 ms/op
     p(99.0000) =     10.256 ms/op
     p(99.9000) =     25.650 ms/op
     p(99.9900) =     60.162 ms/op
     p(99.9990) =     61.485 ms/op
     p(99.9999) =     61.735 ms/op
    p(100.0000) =     61.735 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.538 ±(99.9%) 0.320 ms/op
# Warmup Iteration   2: 7.419 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 5.785 ±(99.9%) 0.020 ms/op
Iteration   1: 5.909 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.880 ms/op
                 getUser·p0.50:   5.513 ms/op
                 getUser·p0.90:   7.307 ms/op
                 getUser·p0.95:   9.110 ms/op
                 getUser·p0.99:   12.927 ms/op
                 getUser·p0.999:  25.199 ms/op
                 getUser·p0.9999: 27.905 ms/op
                 getUser·p1.00:   29.557 ms/op

Iteration   2: 5.580 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.265 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   6.586 ms/op
                 getUser·p0.95:   7.520 ms/op
                 getUser·p0.99:   11.076 ms/op
                 getUser·p0.999:  25.132 ms/op
                 getUser·p0.9999: 36.324 ms/op
                 getUser·p1.00:   38.207 ms/op

Iteration   3: 5.660 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.548 ms/op
                 getUser·p0.50:   5.423 ms/op
                 getUser·p0.90:   6.726 ms/op
                 getUser·p0.95:   7.430 ms/op
                 getUser·p0.99:   9.896 ms/op
                 getUser·p0.999:  26.132 ms/op
                 getUser·p0.9999: 34.394 ms/op
                 getUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168039
  mean =      5.713 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 41892 
    [ 5.000,  7.500) = 115481 
    [ 7.500, 10.000) = 7633 
    [10.000, 12.500) = 1963 
    [12.500, 15.000) = 594 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.880 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      6.824 ms/op
     p(95.0000) =      8.028 ms/op
     p(99.0000) =     11.305 ms/op
     p(99.9000) =     25.231 ms/op
     p(99.9900) =     34.865 ms/op
     p(99.9990) =     38.207 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


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
# Warmup Iteration   1: 23.253 ±(99.9%) 0.422 ms/op
# Warmup Iteration   2: 8.795 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.747 ±(99.9%) 0.031 ms/op
Iteration   1: 6.946 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.912 ms/op
                 listUser·p0.50:   6.586 ms/op
                 listUser·p0.90:   8.438 ms/op
                 listUser·p0.95:   9.765 ms/op
                 listUser·p0.99:   13.402 ms/op
                 listUser·p0.999:  27.257 ms/op
                 listUser·p0.9999: 29.603 ms/op
                 listUser·p1.00:   31.425 ms/op

Iteration   2: 6.601 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.801 ms/op
                 listUser·p0.50:   6.234 ms/op
                 listUser·p0.90:   7.692 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   13.156 ms/op
                 listUser·p0.999:  32.328 ms/op
                 listUser·p0.9999: 38.611 ms/op
                 listUser·p1.00:   39.387 ms/op

Iteration   3: 6.759 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.658 ms/op
                 listUser·p0.50:   6.455 ms/op
                 listUser·p0.90:   7.897 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   12.325 ms/op
                 listUser·p0.999:  39.107 ms/op
                 listUser·p0.9999: 43.182 ms/op
                 listUser·p1.00:   45.679 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141802
  mean =      6.765 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2314 
    [ 5.000, 10.000) = 134459 
    [10.000, 15.000) = 4390 
    [15.000, 20.000) = 348 
    [20.000, 25.000) = 20 
    [25.000, 30.000) = 115 
    [30.000, 35.000) = 61 
    [35.000, 40.000) = 58 
    [40.000, 45.000) = 36 

  Percentiles, ms/op:
      p(0.0000) =      2.658 ms/op
     p(50.0000) =      6.414 ms/op
     p(90.0000) =      8.020 ms/op
     p(95.0000) =      9.290 ms/op
     p(99.0000) =     12.780 ms/op
     p(99.9000) =     30.481 ms/op
     p(99.9900) =     41.931 ms/op
     p(99.9990) =     45.021 ms/op
     p(99.9999) =     45.679 ms/op
    p(100.0000) =     45.679 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.384 ± 3.213  ops/ms
ClientPb.existUser                       thrpt       3   5.775 ± 0.376  ops/ms
ClientPb.getUser                         thrpt       3   5.330 ± 1.841  ops/ms
ClientPb.listUser                        thrpt       3   4.684 ± 1.015  ops/ms
ClientPb.createUser                       avgt       3   5.801 ± 2.350   ms/op
ClientPb.existUser                        avgt       3   5.402 ± 1.351   ms/op
ClientPb.getUser                          avgt       3   5.783 ± 3.372   ms/op
ClientPb.listUser                         avgt       3   6.683 ± 2.916   ms/op
ClientPb.createUser                     sample  167304   5.734 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.021           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.456           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.971           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.954           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.502           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.397           ms/op
ClientPb.createUser:createUser·p0.9999  sample          45.875           ms/op
ClientPb.createUser:createUser·p1.00    sample          49.086           ms/op
ClientPb.existUser                      sample  176405   5.439 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.628           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.161           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.578           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.569           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.256           ms/op
ClientPb.existUser:existUser·p0.999     sample          25.650           ms/op
ClientPb.existUser:existUser·p0.9999    sample          60.162           ms/op
ClientPb.existUser:existUser·p1.00      sample          61.735           ms/op
ClientPb.getUser                        sample  168039   5.713 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.880           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.407           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.824           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.028           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.305           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.231           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.865           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.207           ms/op
ClientPb.listUser                       sample  141802   6.765 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.658           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.414           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.020           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.290           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.780           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.481           ms/op
ClientPb.listUser:listUser·p0.9999      sample          41.931           ms/op
ClientPb.listUser:listUser·p1.00        sample          45.679           ms/op
