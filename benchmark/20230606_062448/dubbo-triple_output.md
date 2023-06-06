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
# Warmup Iteration   1: 1.152 ops/ms
# Warmup Iteration   2: 2.256 ops/ms
# Warmup Iteration   3: 4.745 ops/ms
Iteration   1: 5.684 ops/ms
Iteration   2: 5.789 ops/ms
Iteration   3: 5.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.757 ±(99.9%) 1.162 ops/ms [Average]
  (min, avg, max) = (5.684, 5.757, 5.798), stdev = 0.064
  CI (99.9%): [4.595, 6.918] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.096 ops/ms
# Warmup Iteration   2: 5.952 ops/ms
# Warmup Iteration   3: 5.877 ops/ms
Iteration   1: 6.322 ops/ms
Iteration   2: 6.960 ops/ms
Iteration   3: 7.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.836 ±(99.9%) 8.491 ops/ms [Average]
  (min, avg, max) = (6.322, 6.836, 7.227), stdev = 0.465
  CI (99.9%): [≈ 0, 15.327] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.999 ops/ms
# Warmup Iteration   2: 5.925 ops/ms
# Warmup Iteration   3: 6.279 ops/ms
Iteration   1: 6.045 ops/ms
Iteration   2: 6.599 ops/ms
Iteration   3: 6.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.389 ±(99.9%) 5.474 ops/ms [Average]
  (min, avg, max) = (6.045, 6.389, 6.599), stdev = 0.300
  CI (99.9%): [0.915, 11.863] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.872 ops/ms
# Warmup Iteration   2: 5.157 ops/ms
# Warmup Iteration   3: 5.401 ops/ms
Iteration   1: 5.292 ops/ms
Iteration   2: 5.225 ops/ms
Iteration   3: 5.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.185 ±(99.9%) 2.407 ops/ms [Average]
  (min, avg, max) = (5.038, 5.185, 5.292), stdev = 0.132
  CI (99.9%): [2.778, 7.592] (assumes normal distribution)


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
# Warmup Iteration   1: 20.128 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 6.389 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.688 ±(99.9%) 0.008 ms/op
Iteration   1: 5.242 ±(99.9%) 0.011 ms/op
Iteration   2: 5.179 ±(99.9%) 0.011 ms/op
Iteration   3: 5.375 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.265 ±(99.9%) 1.824 ms/op [Average]
  (min, avg, max) = (5.179, 5.265, 5.375), stdev = 0.100
  CI (99.9%): [3.441, 7.090] (assumes normal distribution)


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
# Warmup Iteration   1: 15.919 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.074 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.288 ±(99.9%) 0.007 ms/op
Iteration   1: 5.142 ±(99.9%) 0.008 ms/op
Iteration   2: 5.209 ±(99.9%) 0.009 ms/op
Iteration   3: 5.332 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.228 ±(99.9%) 1.756 ms/op [Average]
  (min, avg, max) = (5.142, 5.228, 5.332), stdev = 0.096
  CI (99.9%): [3.471, 6.984] (assumes normal distribution)


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
# Warmup Iteration   1: 16.934 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.903 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.312 ±(99.9%) 0.009 ms/op
Iteration   1: 5.373 ±(99.9%) 0.012 ms/op
Iteration   2: 5.419 ±(99.9%) 0.012 ms/op
Iteration   3: 5.149 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.314 ±(99.9%) 2.634 ms/op [Average]
  (min, avg, max) = (5.149, 5.314, 5.419), stdev = 0.144
  CI (99.9%): [2.679, 7.948] (assumes normal distribution)


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
# Warmup Iteration   1: 18.433 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 7.624 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.386 ±(99.9%) 0.017 ms/op
Iteration   1: 6.644 ±(99.9%) 0.017 ms/op
Iteration   2: 6.438 ±(99.9%) 0.016 ms/op
Iteration   3: 6.100 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.394 ±(99.9%) 5.007 ms/op [Average]
  (min, avg, max) = (6.100, 6.394, 6.644), stdev = 0.274
  CI (99.9%): [1.387, 11.401] (assumes normal distribution)


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
# Warmup Iteration   1: 16.520 ±(99.9%) 0.259 ms/op
# Warmup Iteration   2: 7.280 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.452 ±(99.9%) 0.022 ms/op
Iteration   1: 5.462 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.208 ms/op
                 createUser·p0.50:   5.071 ms/op
                 createUser·p0.90:   6.867 ms/op
                 createUser·p0.95:   8.165 ms/op
                 createUser·p0.99:   12.386 ms/op
                 createUser·p0.999:  21.520 ms/op
                 createUser·p0.9999: 41.138 ms/op
                 createUser·p1.00:   42.336 ms/op

Iteration   2: 5.238 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.561 ms/op
                 createUser·p0.50:   4.956 ms/op
                 createUser·p0.90:   6.414 ms/op
                 createUser·p0.95:   7.209 ms/op
                 createUser·p0.99:   9.660 ms/op
                 createUser·p0.999:  26.934 ms/op
                 createUser·p0.9999: 31.308 ms/op
                 createUser·p1.00:   33.554 ms/op

Iteration   3: 5.384 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.306 ms/op
                 createUser·p0.50:   5.022 ms/op
                 createUser·p0.90:   6.783 ms/op
                 createUser·p0.95:   7.815 ms/op
                 createUser·p0.99:   10.093 ms/op
                 createUser·p0.999:  25.826 ms/op
                 createUser·p0.9999: 30.321 ms/op
                 createUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178959
  mean =      5.360 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 88091 
    [ 5.000, 10.000) = 88335 
    [10.000, 15.000) = 2210 
    [15.000, 20.000) = 115 
    [20.000, 25.000) = 48 
    [25.000, 30.000) = 102 
    [30.000, 35.000) = 26 
    [35.000, 40.000) = 21 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.561 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.725 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     22.657 ms/op
     p(99.9900) =     39.715 ms/op
     p(99.9990) =     42.285 ms/op
     p(99.9999) =     42.336 ms/op
    p(100.0000) =     42.336 ms/op


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
# Warmup Iteration   1: 17.351 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 5.744 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.026 ±(99.9%) 0.021 ms/op
Iteration   1: 5.145 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.878 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.373 ms/op
                 existUser·p0.95:   7.414 ms/op
                 existUser·p0.99:   10.371 ms/op
                 existUser·p0.999:  25.650 ms/op
                 existUser·p0.9999: 31.490 ms/op
                 existUser·p1.00:   32.571 ms/op

Iteration   2: 5.058 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.101 ms/op
                 existUser·p0.50:   4.841 ms/op
                 existUser·p0.90:   6.169 ms/op
                 existUser·p0.95:   6.881 ms/op
                 existUser·p0.99:   9.847 ms/op
                 existUser·p0.999:  28.391 ms/op
                 existUser·p0.9999: 33.052 ms/op
                 existUser·p1.00:   34.013 ms/op

Iteration   3: 4.935 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.020 ms/op
                 existUser·p0.50:   4.661 ms/op
                 existUser·p0.90:   6.185 ms/op
                 existUser·p0.95:   7.193 ms/op
                 existUser·p0.99:   10.084 ms/op
                 existUser·p0.999:  19.434 ms/op
                 existUser·p0.9999: 28.544 ms/op
                 existUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 190191
  mean =      5.045 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 113 
    [ 2.500,  5.000) = 115930 
    [ 5.000,  7.500) = 66441 
    [ 7.500, 10.000) = 5724 
    [10.000, 12.500) = 1442 
    [12.500, 15.000) = 326 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      4.801 ms/op
     p(90.0000) =      6.226 ms/op
     p(95.0000) =      7.152 ms/op
     p(99.0000) =     10.094 ms/op
     p(99.9000) =     24.766 ms/op
     p(99.9900) =     32.080 ms/op
     p(99.9990) =     33.777 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 15.392 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 6.067 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.509 ±(99.9%) 0.022 ms/op
Iteration   1: 5.226 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.470 ms/op
                 getUser·p0.50:   4.891 ms/op
                 getUser·p0.90:   6.570 ms/op
                 getUser·p0.95:   7.814 ms/op
                 getUser·p0.99:   11.403 ms/op
                 getUser·p0.999:  26.699 ms/op
                 getUser·p0.9999: 41.083 ms/op
                 getUser·p1.00:   41.157 ms/op

Iteration   2: 5.131 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.441 ms/op
                 getUser·p0.50:   4.833 ms/op
                 getUser·p0.90:   6.349 ms/op
                 getUser·p0.95:   7.561 ms/op
                 getUser·p0.99:   10.961 ms/op
                 getUser·p0.999:  25.362 ms/op
                 getUser·p0.9999: 28.508 ms/op
                 getUser·p1.00:   31.916 ms/op

Iteration   3: 5.295 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.404 ms/op
                 getUser·p0.50:   4.973 ms/op
                 getUser·p0.90:   6.783 ms/op
                 getUser·p0.95:   7.954 ms/op
                 getUser·p0.99:   10.650 ms/op
                 getUser·p0.999:  28.450 ms/op
                 getUser·p0.9999: 32.764 ms/op
                 getUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 183943
  mean =      5.216 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 101437 
    [ 5.000, 10.000) = 79495 
    [10.000, 15.000) = 2569 
    [15.000, 20.000) = 212 
    [20.000, 25.000) = 40 
    [25.000, 30.000) = 115 
    [30.000, 35.000) = 47 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.562 ms/op
     p(95.0000) =      7.791 ms/op
     p(99.0000) =     10.994 ms/op
     p(99.9000) =     25.630 ms/op
     p(99.9900) =     40.829 ms/op
     p(99.9990) =     41.102 ms/op
     p(99.9999) =     41.157 ms/op
    p(100.0000) =     41.157 ms/op


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
# Warmup Iteration   1: 19.213 ±(99.9%) 0.340 ms/op
# Warmup Iteration   2: 7.916 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.179 ±(99.9%) 0.028 ms/op
Iteration   1: 6.521 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.990 ms/op
                 listUser·p0.50:   6.095 ms/op
                 listUser·p0.90:   8.454 ms/op
                 listUser·p0.95:   9.814 ms/op
                 listUser·p0.99:   12.911 ms/op
                 listUser·p0.999:  25.754 ms/op
                 listUser·p0.9999: 27.921 ms/op
                 listUser·p1.00:   28.738 ms/op

Iteration   2: 6.200 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   5.833 ms/op
                 listUser·p0.90:   7.733 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   12.255 ms/op
                 listUser·p0.999:  28.751 ms/op
                 listUser·p0.9999: 31.775 ms/op
                 listUser·p1.00:   33.227 ms/op

Iteration   3: 6.344 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.937 ms/op
                 listUser·p0.50:   5.931 ms/op
                 listUser·p0.90:   7.946 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  24.659 ms/op
                 listUser·p0.9999: 30.135 ms/op
                 listUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151075
  mean =      6.352 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 14049 
    [ 5.000,  7.500) = 115862 
    [ 7.500, 10.000) = 15967 
    [10.000, 12.500) = 3782 
    [12.500, 15.000) = 883 
    [15.000, 17.500) = 215 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 104 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.220 ms/op
     p(50.0000) =      5.947 ms/op
     p(90.0000) =      8.061 ms/op
     p(95.0000) =      9.355 ms/op
     p(99.0000) =     12.354 ms/op
     p(99.9000) =     26.376 ms/op
     p(99.9900) =     30.700 ms/op
     p(99.9990) =     32.541 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.757 ± 1.162  ops/ms
ClientPb.existUser                       thrpt       3   6.836 ± 8.491  ops/ms
ClientPb.getUser                         thrpt       3   6.389 ± 5.474  ops/ms
ClientPb.listUser                        thrpt       3   5.185 ± 2.407  ops/ms
ClientPb.createUser                       avgt       3   5.265 ± 1.824   ms/op
ClientPb.existUser                        avgt       3   5.228 ± 1.756   ms/op
ClientPb.getUser                          avgt       3   5.314 ± 2.634   ms/op
ClientPb.listUser                         avgt       3   6.394 ± 5.007   ms/op
ClientPb.createUser                     sample  178959   5.360 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.561           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.014           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.685           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.725           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.748           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.657           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.715           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.336           ms/op
ClientPb.existUser                      sample  190191   5.045 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.020           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.801           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.226           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.152           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.094           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.766           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.080           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.013           ms/op
ClientPb.getUser                        sample  183943   5.216 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.404           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.899           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.562           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.791           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.994           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.630           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.829           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.157           ms/op
ClientPb.listUser                       sample  151075   6.352 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.220           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.947           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.061           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.355           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.354           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.376           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.700           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.227           ms/op
