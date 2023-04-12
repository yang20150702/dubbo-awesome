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
# Warmup Iteration   1: 0.950 ops/ms
# Warmup Iteration   2: 2.180 ops/ms
# Warmup Iteration   3: 5.302 ops/ms
Iteration   1: 5.770 ops/ms
Iteration   2: 5.799 ops/ms
Iteration   3: 5.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.821 ±(99.9%) 1.187 ops/ms [Average]
  (min, avg, max) = (5.770, 5.821, 5.895), stdev = 0.065
  CI (99.9%): [4.634, 7.009] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.633 ops/ms
# Warmup Iteration   2: 4.989 ops/ms
# Warmup Iteration   3: 5.850 ops/ms
Iteration   1: 6.310 ops/ms
Iteration   2: 6.279 ops/ms
Iteration   3: 6.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.273 ±(99.9%) 0.732 ops/ms [Average]
  (min, avg, max) = (6.231, 6.273, 6.310), stdev = 0.040
  CI (99.9%): [5.541, 7.005] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.339 ops/ms
# Warmup Iteration   2: 4.268 ops/ms
# Warmup Iteration   3: 5.657 ops/ms
Iteration   1: 5.946 ops/ms
Iteration   2: 5.855 ops/ms
Iteration   3: 5.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.835 ±(99.9%) 2.240 ops/ms [Average]
  (min, avg, max) = (5.703, 5.835, 5.946), stdev = 0.123
  CI (99.9%): [3.595, 8.074] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.503 ops/ms
# Warmup Iteration   2: 3.812 ops/ms
# Warmup Iteration   3: 5.044 ops/ms
Iteration   1: 5.324 ops/ms
Iteration   2: 5.155 ops/ms
Iteration   3: 5.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.206 ±(99.9%) 1.882 ops/ms [Average]
  (min, avg, max) = (5.138, 5.206, 5.324), stdev = 0.103
  CI (99.9%): [3.324, 7.087] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.280 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.546 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.782 ±(99.9%) 0.009 ms/op
Iteration   1: 5.372 ±(99.9%) 0.015 ms/op
Iteration   2: 5.304 ±(99.9%) 0.013 ms/op
Iteration   3: 5.257 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.311 ±(99.9%) 1.059 ms/op [Average]
  (min, avg, max) = (5.257, 5.311, 5.372), stdev = 0.058
  CI (99.9%): [4.252, 6.370] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 14.492 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.956 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.081 ±(99.9%) 0.010 ms/op
Iteration   1: 5.252 ±(99.9%) 0.007 ms/op
Iteration   2: 5.010 ±(99.9%) 0.013 ms/op
Iteration   3: 4.885 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.049 ±(99.9%) 3.399 ms/op [Average]
  (min, avg, max) = (4.885, 5.049, 5.252), stdev = 0.186
  CI (99.9%): [1.650, 8.448] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.107 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.854 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.305 ±(99.9%) 0.010 ms/op
Iteration   1: 5.474 ±(99.9%) 0.009 ms/op
Iteration   2: 5.115 ±(99.9%) 0.020 ms/op
Iteration   3: 5.289 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.293 ±(99.9%) 3.273 ms/op [Average]
  (min, avg, max) = (5.115, 5.293, 5.474), stdev = 0.179
  CI (99.9%): [2.020, 8.565] (assumes normal distribution)


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
# Warmup Iteration   1: 18.547 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 7.171 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.240 ±(99.9%) 0.017 ms/op
Iteration   1: 5.940 ±(99.9%) 0.016 ms/op
Iteration   2: 6.613 ±(99.9%) 0.017 ms/op
Iteration   3: 6.423 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.325 ±(99.9%) 6.325 ms/op [Average]
  (min, avg, max) = (5.940, 6.325, 6.613), stdev = 0.347
  CI (99.9%): [≈ 0, 12.651] (assumes normal distribution)


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
# Warmup Iteration   1: 16.972 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 6.872 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 6.023 ±(99.9%) 0.027 ms/op
Iteration   1: 5.446 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.396 ms/op
                 createUser·p0.50:   5.186 ms/op
                 createUser·p0.90:   6.717 ms/op
                 createUser·p0.95:   7.627 ms/op
                 createUser·p0.99:   9.601 ms/op
                 createUser·p0.999:  24.239 ms/op
                 createUser·p0.9999: 27.529 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   2: 5.291 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.040 ms/op
                 createUser·p0.50:   5.071 ms/op
                 createUser·p0.90:   6.423 ms/op
                 createUser·p0.95:   7.070 ms/op
                 createUser·p0.99:   9.257 ms/op
                 createUser·p0.999:  27.034 ms/op
                 createUser·p0.9999: 31.490 ms/op
                 createUser·p1.00:   32.670 ms/op

Iteration   3: 5.392 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.351 ms/op
                 createUser·p0.50:   5.153 ms/op
                 createUser·p0.90:   6.365 ms/op
                 createUser·p0.95:   7.029 ms/op
                 createUser·p0.99:   9.787 ms/op
                 createUser·p0.999:  28.082 ms/op
                 createUser·p0.9999: 31.394 ms/op
                 createUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178441
  mean =      5.376 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 73019 
    [ 5.000,  7.500) = 97989 
    [ 7.500, 10.000) = 6125 
    [10.000, 12.500) = 798 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 87 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.040 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.488 ms/op
     p(95.0000) =      7.258 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     24.674 ms/op
     p(99.9900) =     30.883 ms/op
     p(99.9990) =     32.873 ms/op
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
# Warmup Iteration   1: 16.104 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 5.920 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.332 ±(99.9%) 0.019 ms/op
Iteration   1: 5.184 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.733 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.365 ms/op
                 existUser·p0.95:   7.111 ms/op
                 existUser·p0.99:   9.142 ms/op
                 existUser·p0.999:  19.245 ms/op
                 existUser·p0.9999: 25.089 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   2: 4.933 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.421 ms/op
                 existUser·p0.50:   4.768 ms/op
                 existUser·p0.90:   5.825 ms/op
                 existUser·p0.95:   6.488 ms/op
                 existUser·p0.99:   8.603 ms/op
                 existUser·p0.999:  14.820 ms/op
                 existUser·p0.9999: 25.052 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   3: 5.125 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.249 ms/op
                 existUser·p0.50:   4.915 ms/op
                 existUser·p0.90:   6.218 ms/op
                 existUser·p0.95:   6.865 ms/op
                 existUser·p0.99:   9.019 ms/op
                 existUser·p0.999:  17.912 ms/op
                 existUser·p0.9999: 27.492 ms/op
                 existUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188832
  mean =      5.078 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 109685 
    [ 5.000,  7.500) = 73654 
    [ 7.500, 10.000) = 4360 
    [10.000, 12.500) = 687 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.733 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      6.160 ms/op
     p(95.0000) =      6.849 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     25.687 ms/op
     p(99.9990) =     27.926 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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
# Warmup Iteration   1: 16.764 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 6.450 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.793 ±(99.9%) 0.022 ms/op
Iteration   1: 5.548 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.449 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   6.816 ms/op
                 getUser·p0.95:   7.889 ms/op
                 getUser·p0.99:   11.715 ms/op
                 getUser·p0.999:  18.055 ms/op
                 getUser·p0.9999: 29.769 ms/op
                 getUser·p1.00:   32.670 ms/op

Iteration   2: 5.807 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.646 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   7.152 ms/op
                 getUser·p0.95:   8.372 ms/op
                 getUser·p0.99:   12.173 ms/op
                 getUser·p0.999:  26.455 ms/op
                 getUser·p0.9999: 32.325 ms/op
                 getUser·p1.00:   33.063 ms/op

Iteration   3: 5.514 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.179 ms/op
                 getUser·p0.50:   5.251 ms/op
                 getUser·p0.90:   6.619 ms/op
                 getUser·p0.95:   7.487 ms/op
                 getUser·p0.99:   10.191 ms/op
                 getUser·p0.999:  26.868 ms/op
                 getUser·p0.9999: 34.210 ms/op
                 getUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170755
  mean =      5.620 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 56060 
    [ 5.000,  7.500) = 103986 
    [ 7.500, 10.000) = 7827 
    [10.000, 12.500) = 1648 
    [12.500, 15.000) = 696 
    [15.000, 17.500) = 271 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.179 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      6.865 ms/op
     p(95.0000) =      7.899 ms/op
     p(99.0000) =     11.403 ms/op
     p(99.9000) =     25.239 ms/op
     p(99.9900) =     33.421 ms/op
     p(99.9990) =     34.849 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 19.267 ±(99.9%) 0.335 ms/op
# Warmup Iteration   2: 7.455 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 6.608 ±(99.9%) 0.025 ms/op
Iteration   1: 6.313 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.691 ms/op
                 listUser·p0.50:   6.013 ms/op
                 listUser·p0.90:   7.463 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   11.485 ms/op
                 listUser·p0.999:  23.826 ms/op
                 listUser·p0.9999: 26.458 ms/op
                 listUser·p1.00:   27.525 ms/op

Iteration   2: 6.434 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.915 ms/op
                 listUser·p0.50:   6.095 ms/op
                 listUser·p0.90:   7.807 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   11.239 ms/op
                 listUser·p0.999:  29.393 ms/op
                 listUser·p0.9999: 35.662 ms/op
                 listUser·p1.00:   37.224 ms/op

Iteration   3: 6.721 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.052 ms/op
                 listUser·p0.50:   6.308 ms/op
                 listUser·p0.90:   8.241 ms/op
                 listUser·p0.95:   9.208 ms/op
                 listUser·p0.99:   12.419 ms/op
                 listUser·p0.999:  24.461 ms/op
                 listUser·p0.9999: 28.926 ms/op
                 listUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147996
  mean =      6.485 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 5657 
    [ 5.000,  7.500) = 121283 
    [ 7.500, 10.000) = 17318 
    [10.000, 12.500) = 2631 
    [12.500, 15.000) = 651 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.915 ms/op
     p(50.0000) =      6.128 ms/op
     p(90.0000) =      7.913 ms/op
     p(95.0000) =      8.913 ms/op
     p(99.0000) =     11.665 ms/op
     p(99.9000) =     25.428 ms/op
     p(99.9900) =     33.581 ms/op
     p(99.9990) =     37.099 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.821 ± 1.187  ops/ms
ClientPb.existUser                       thrpt       3   6.273 ± 0.732  ops/ms
ClientPb.getUser                         thrpt       3   5.835 ± 2.240  ops/ms
ClientPb.listUser                        thrpt       3   5.206 ± 1.882  ops/ms
ClientPb.createUser                       avgt       3   5.311 ± 1.059   ms/op
ClientPb.existUser                        avgt       3   5.049 ± 3.399   ms/op
ClientPb.getUser                          avgt       3   5.293 ± 3.273   ms/op
ClientPb.listUser                         avgt       3   6.325 ± 6.325   ms/op
ClientPb.createUser                     sample  178441   5.376 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.040           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.136           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.488           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.258           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.585           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.674           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.883           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.899           ms/op
ClientPb.existUser                      sample  188832   5.078 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.733           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.866           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.160           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.849           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.946           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.924           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.687           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.984           ms/op
ClientPb.getUser                        sample  170755   5.620 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.179           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.300           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.865           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.899           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.403           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.239           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.421           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.127           ms/op
ClientPb.listUser                       sample  147996   6.485 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.915           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.128           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.913           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.913           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.665           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.428           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.581           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.224           ms/op
