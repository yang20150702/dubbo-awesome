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
# Warmup Iteration   1: 1.769 ops/ms
# Warmup Iteration   2: 3.812 ops/ms
# Warmup Iteration   3: 6.910 ops/ms
Iteration   1: 7.182 ops/ms
Iteration   2: 8.067 ops/ms
Iteration   3: 7.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.714 ±(99.9%) 8.557 ops/ms [Average]
  (min, avg, max) = (7.182, 7.714, 8.067), stdev = 0.469
  CI (99.9%): [≈ 0, 16.270] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.369 ops/ms
# Warmup Iteration   2: 6.790 ops/ms
# Warmup Iteration   3: 8.150 ops/ms
Iteration   1: 8.237 ops/ms
Iteration   2: 8.493 ops/ms
Iteration   3: 8.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.399 ±(99.9%) 2.569 ops/ms [Average]
  (min, avg, max) = (8.237, 8.399, 8.493), stdev = 0.141
  CI (99.9%): [5.830, 10.968] (assumes normal distribution)


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
# Warmup Iteration   1: 2.291 ops/ms
# Warmup Iteration   2: 6.771 ops/ms
# Warmup Iteration   3: 7.807 ops/ms
Iteration   1: 8.042 ops/ms
Iteration   2: 7.895 ops/ms
Iteration   3: 7.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.956 ±(99.9%) 1.398 ops/ms [Average]
  (min, avg, max) = (7.895, 7.956, 8.042), stdev = 0.077
  CI (99.9%): [6.558, 9.354] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.281 ops/ms
# Warmup Iteration   2: 6.110 ops/ms
# Warmup Iteration   3: 6.570 ops/ms
Iteration   1: 6.915 ops/ms
Iteration   2: 6.954 ops/ms
Iteration   3: 6.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.840 ±(99.9%) 3.013 ops/ms [Average]
  (min, avg, max) = (6.650, 6.840, 6.954), stdev = 0.165
  CI (99.9%): [3.826, 9.853] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 11.276 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.036 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.391 ±(99.9%) 0.004 ms/op
Iteration   1: 4.093 ±(99.9%) 0.005 ms/op
Iteration   2: 4.012 ±(99.9%) 0.005 ms/op
Iteration   3: 3.978 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.028 ±(99.9%) 1.077 ms/op [Average]
  (min, avg, max) = (3.978, 4.028, 4.093), stdev = 0.059
  CI (99.9%): [2.951, 5.105] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.022 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.521 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.002 ms/op
Iteration   1: 3.851 ±(99.9%) 0.011 ms/op
Iteration   2: 3.682 ±(99.9%) 0.011 ms/op
Iteration   3: 3.750 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.761 ±(99.9%) 1.556 ms/op [Average]
  (min, avg, max) = (3.682, 3.761, 3.851), stdev = 0.085
  CI (99.9%): [2.205, 5.317] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.695 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.867 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.007 ms/op
Iteration   1: 4.022 ±(99.9%) 0.006 ms/op
Iteration   2: 3.780 ±(99.9%) 0.011 ms/op
Iteration   3: 3.888 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.897 ±(99.9%) 2.209 ms/op [Average]
  (min, avg, max) = (3.780, 3.897, 4.022), stdev = 0.121
  CI (99.9%): [1.688, 6.106] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.301 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.763 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.804 ±(99.9%) 0.008 ms/op
Iteration   1: 4.684 ±(99.9%) 0.015 ms/op
Iteration   2: 4.633 ±(99.9%) 0.012 ms/op
Iteration   3: 4.697 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.671 ±(99.9%) 0.618 ms/op [Average]
  (min, avg, max) = (4.633, 4.671, 4.697), stdev = 0.034
  CI (99.9%): [4.053, 5.289] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.301 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.919 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.348 ±(99.9%) 0.019 ms/op
Iteration   1: 4.074 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   7.717 ms/op
                 createUser·p0.999:  23.212 ms/op
                 createUser·p0.9999: 25.461 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   2: 4.054 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   7.578 ms/op
                 createUser·p0.999:  16.433 ms/op
                 createUser·p0.9999: 27.992 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   3: 4.057 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.950 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  27.606 ms/op
                 createUser·p0.9999: 32.506 ms/op
                 createUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236217
  mean =      4.061 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 391 
    [ 2.500,  5.000) = 222456 
    [ 5.000,  7.500) = 11056 
    [ 7.500, 10.000) = 1461 
    [10.000, 12.500) = 391 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     23.368 ms/op
     p(99.9900) =     31.593 ms/op
     p(99.9990) =     33.319 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.005 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.455 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.238 ±(99.9%) 0.013 ms/op
Iteration   1: 3.869 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.825 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   7.627 ms/op
                 existUser·p0.999:  23.016 ms/op
                 existUser·p0.9999: 25.854 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   2: 3.849 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.933 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.783 ms/op
                 existUser·p0.999:  15.460 ms/op
                 existUser·p0.9999: 26.673 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   3: 3.924 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.374 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.014 ms/op
                 existUser·p0.99:   6.570 ms/op
                 existUser·p0.999:  18.776 ms/op
                 existUser·p0.9999: 29.678 ms/op
                 existUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247291
  mean =      3.880 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 389 
    [ 2.500,  5.000) = 235911 
    [ 5.000,  7.500) = 9310 
    [ 7.500, 10.000) = 1221 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     18.624 ms/op
     p(99.9900) =     28.344 ms/op
     p(99.9990) =     30.114 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 12.446 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 4.595 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.163 ±(99.9%) 0.012 ms/op
Iteration   1: 4.045 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   7.471 ms/op
                 getUser·p0.999:  22.151 ms/op
                 getUser·p0.9999: 25.712 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   2: 3.957 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.228 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   7.922 ms/op
                 getUser·p0.999:  13.684 ms/op
                 getUser·p0.9999: 30.865 ms/op
                 getUser·p1.00:   31.130 ms/op

Iteration   3: 3.836 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  24.909 ms/op
                 getUser·p0.9999: 31.248 ms/op
                 getUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 243208
  mean =      3.944 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 122 
    [ 2.500,  5.000) = 232474 
    [ 5.000,  7.500) = 8497 
    [ 7.500, 10.000) = 1285 
    [10.000, 12.500) = 453 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.200 ms/op
     p(99.9000) =     22.112 ms/op
     p(99.9900) =     30.715 ms/op
     p(99.9990) =     31.621 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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
# Warmup Iteration   1: 14.298 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 5.573 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.065 ±(99.9%) 0.018 ms/op
Iteration   1: 4.775 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.796 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   8.730 ms/op
                 listUser·p0.999:  24.640 ms/op
                 listUser·p0.9999: 28.865 ms/op
                 listUser·p1.00:   29.655 ms/op

Iteration   2: 4.619 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.732 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   8.118 ms/op
                 listUser·p0.999:  19.333 ms/op
                 listUser·p0.9999: 29.065 ms/op
                 listUser·p1.00:   29.098 ms/op

Iteration   3: 4.652 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.626 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   9.077 ms/op
                 listUser·p0.999:  17.048 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204921
  mean =      4.681 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 180784 
    [ 5.000,  7.500) = 19377 
    [ 7.500, 10.000) = 3670 
    [10.000, 12.500) = 500 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.796 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     29.032 ms/op
     p(99.9990) =     29.446 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.714 ± 8.557  ops/ms
ClientPb.existUser                       thrpt       3   8.399 ± 2.569  ops/ms
ClientPb.getUser                         thrpt       3   7.956 ± 1.398  ops/ms
ClientPb.listUser                        thrpt       3   6.840 ± 3.013  ops/ms
ClientPb.createUser                       avgt       3   4.028 ± 1.077   ms/op
ClientPb.existUser                        avgt       3   3.761 ± 1.556   ms/op
ClientPb.getUser                          avgt       3   3.897 ± 2.209   ms/op
ClientPb.listUser                         avgt       3   4.671 ± 0.618   ms/op
ClientPb.createUser                     sample  236217   4.061 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.376           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.653           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.104           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.455           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.368           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.593           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.554           ms/op
ClientPb.existUser                      sample  247291   3.880 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.374           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.152           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.624           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.344           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.031           ms/op
ClientPb.getUser                        sample  243208   3.944 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.112           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.858           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.200           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.112           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.715           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.654           ms/op
ClientPb.listUser                       sample  204921   4.681 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.796           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.333           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.032           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.655           ms/op
