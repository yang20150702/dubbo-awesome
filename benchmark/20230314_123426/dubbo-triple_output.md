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
# Warmup Iteration   1: 1.630 ops/ms
# Warmup Iteration   2: 4.131 ops/ms
# Warmup Iteration   3: 7.401 ops/ms
Iteration   1: 7.731 ops/ms
Iteration   2: 8.251 ops/ms
Iteration   3: 7.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.987 ±(99.9%) 4.739 ops/ms [Average]
  (min, avg, max) = (7.731, 7.987, 8.251), stdev = 0.260
  CI (99.9%): [3.248, 12.726] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.227 ops/ms
# Warmup Iteration   2: 6.604 ops/ms
# Warmup Iteration   3: 8.000 ops/ms
Iteration   1: 8.288 ops/ms
Iteration   2: 8.379 ops/ms
Iteration   3: 8.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.508 ±(99.9%) 5.579 ops/ms [Average]
  (min, avg, max) = (8.288, 8.508, 8.857), stdev = 0.306
  CI (99.9%): [2.929, 14.087] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.040 ops/ms
# Warmup Iteration   2: 6.265 ops/ms
# Warmup Iteration   3: 7.479 ops/ms
Iteration   1: 7.631 ops/ms
Iteration   2: 7.888 ops/ms
Iteration   3: 7.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.761 ±(99.9%) 2.349 ops/ms [Average]
  (min, avg, max) = (7.631, 7.761, 7.888), stdev = 0.129
  CI (99.9%): [5.412, 10.109] (assumes normal distribution)


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
# Warmup Iteration   1: 2.108 ops/ms
# Warmup Iteration   2: 5.227 ops/ms
# Warmup Iteration   3: 6.535 ops/ms
Iteration   1: 6.547 ops/ms
Iteration   2: 6.722 ops/ms
Iteration   3: 6.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.724 ±(99.9%) 3.261 ops/ms [Average]
  (min, avg, max) = (6.547, 6.724, 6.904), stdev = 0.179
  CI (99.9%): [3.464, 9.985] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 12.381 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.315 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.262 ±(99.9%) 0.007 ms/op
Iteration   1: 4.158 ±(99.9%) 0.005 ms/op
Iteration   2: 3.847 ±(99.9%) 0.012 ms/op
Iteration   3: 4.036 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.014 ±(99.9%) 2.864 ms/op [Average]
  (min, avg, max) = (3.847, 4.014, 4.158), stdev = 0.157
  CI (99.9%): [1.150, 6.878] (assumes normal distribution)


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
# Warmup Iteration   1: 11.087 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.287 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.006 ms/op
Iteration   1: 4.171 ±(99.9%) 0.005 ms/op
Iteration   2: 4.072 ±(99.9%) 0.007 ms/op
Iteration   3: 3.966 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.070 ±(99.9%) 1.865 ms/op [Average]
  (min, avg, max) = (3.966, 4.070, 4.171), stdev = 0.102
  CI (99.9%): [2.205, 5.935] (assumes normal distribution)


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
# Warmup Iteration   1: 11.797 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.164 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.340 ±(99.9%) 0.007 ms/op
Iteration   1: 4.118 ±(99.9%) 0.011 ms/op
Iteration   2: 4.076 ±(99.9%) 0.011 ms/op
Iteration   3: 4.034 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.076 ±(99.9%) 0.762 ms/op [Average]
  (min, avg, max) = (4.034, 4.076, 4.118), stdev = 0.042
  CI (99.9%): [3.314, 4.838] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.697 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.675 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.745 ±(99.9%) 0.013 ms/op
Iteration   1: 4.873 ±(99.9%) 0.011 ms/op
Iteration   2: 4.795 ±(99.9%) 0.012 ms/op
Iteration   3: 4.624 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.764 ±(99.9%) 2.322 ms/op [Average]
  (min, avg, max) = (4.624, 4.764, 4.873), stdev = 0.127
  CI (99.9%): [2.442, 7.087] (assumes normal distribution)


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
# Warmup Iteration   1: 12.188 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.732 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.183 ±(99.9%) 0.016 ms/op
Iteration   1: 4.023 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.705 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   7.954 ms/op
                 createUser·p0.999:  21.736 ms/op
                 createUser·p0.9999: 23.824 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   2: 4.057 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.923 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.921 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   7.607 ms/op
                 createUser·p0.999:  12.864 ms/op
                 createUser·p0.9999: 33.554 ms/op
                 createUser·p1.00:   34.210 ms/op

Iteration   3: 4.128 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   5.833 ms/op
                 createUser·p0.99:   8.086 ms/op
                 createUser·p0.999:  29.032 ms/op
                 createUser·p0.9999: 39.780 ms/op
                 createUser·p1.00:   40.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235921
  mean =      4.069 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 216025 
    [ 5.000, 10.000) = 19021 
    [10.000, 15.000) = 521 
    [15.000, 20.000) = 66 
    [20.000, 25.000) = 107 
    [25.000, 30.000) = 82 
    [30.000, 35.000) = 67 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.905 ms/op
     p(99.9000) =     22.315 ms/op
     p(99.9900) =     38.365 ms/op
     p(99.9990) =     40.210 ms/op
     p(99.9999) =     40.436 ms/op
    p(100.0000) =     40.436 ms/op


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
# Warmup Iteration   1: 12.478 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.922 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.013 ms/op
Iteration   1: 4.034 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.792 ms/op
                 existUser·p0.95:   5.612 ms/op
                 existUser·p0.99:   7.979 ms/op
                 existUser·p0.999:  21.289 ms/op
                 existUser·p0.9999: 23.838 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   2: 4.013 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.956 ms/op
                 existUser·p0.99:   7.881 ms/op
                 existUser·p0.999:  12.521 ms/op
                 existUser·p0.9999: 26.450 ms/op
                 existUser·p1.00:   27.853 ms/op

Iteration   3: 4.005 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.327 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   7.561 ms/op
                 existUser·p0.999:  12.256 ms/op
                 existUser·p0.9999: 28.345 ms/op
                 existUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 239062
  mean =      4.017 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 369 
    [ 2.500,  5.000) = 220452 
    [ 5.000,  7.500) = 15281 
    [ 7.500, 10.000) = 2330 
    [10.000, 12.500) = 343 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 88 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     14.253 ms/op
     p(99.9900) =     27.329 ms/op
     p(99.9990) =     28.832 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 13.848 ±(99.9%) 0.225 ms/op
# Warmup Iteration   2: 4.760 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.165 ±(99.9%) 0.013 ms/op
Iteration   1: 4.372 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   4.096 ms/op
                 getUser·p0.90:   5.374 ms/op
                 getUser·p0.95:   6.595 ms/op
                 getUser·p0.99:   9.159 ms/op
                 getUser·p0.999:  22.807 ms/op
                 getUser·p0.9999: 24.751 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   2: 4.042 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.087 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   7.569 ms/op
                 getUser·p0.999:  12.255 ms/op
                 getUser·p0.9999: 27.904 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   3: 4.122 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.581 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.399 ms/op
                 getUser·p0.99:   7.524 ms/op
                 getUser·p0.999:  12.435 ms/op
                 getUser·p0.9999: 29.663 ms/op
                 getUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 230009
  mean =      4.174 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 86 
    [ 2.500,  5.000) = 209229 
    [ 5.000,  7.500) = 17127 
    [ 7.500, 10.000) = 2755 
    [10.000, 12.500) = 518 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      8.282 ms/op
     p(99.9000) =     21.103 ms/op
     p(99.9900) =     28.901 ms/op
     p(99.9990) =     30.854 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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
# Warmup Iteration   1: 18.046 ±(99.9%) 0.255 ms/op
# Warmup Iteration   2: 6.912 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.264 ±(99.9%) 0.021 ms/op
Iteration   1: 5.167 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.560 ms/op
                 listUser·p0.50:   4.891 ms/op
                 listUser·p0.90:   6.013 ms/op
                 listUser·p0.95:   7.520 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  26.935 ms/op
                 listUser·p0.9999: 29.976 ms/op
                 listUser·p1.00:   30.835 ms/op

Iteration   2: 4.819 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.008 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  25.592 ms/op
                 listUser·p0.9999: 28.356 ms/op
                 listUser·p1.00:   29.491 ms/op

Iteration   3: 4.927 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.972 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.406 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  19.726 ms/op
                 listUser·p0.9999: 25.002 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 193203
  mean =      4.967 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 133561 
    [ 5.000,  7.500) = 52921 
    [ 7.500, 10.000) = 5183 
    [10.000, 12.500) = 900 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 120 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.676 ms/op
     p(99.0000) =      9.535 ms/op
     p(99.9000) =     24.936 ms/op
     p(99.9900) =     29.382 ms/op
     p(99.9990) =     30.407 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.987 ± 4.739  ops/ms
ClientPb.existUser                       thrpt       3   8.508 ± 5.579  ops/ms
ClientPb.getUser                         thrpt       3   7.761 ± 2.349  ops/ms
ClientPb.listUser                        thrpt       3   6.724 ± 3.261  ops/ms
ClientPb.createUser                       avgt       3   4.014 ± 2.864   ms/op
ClientPb.existUser                        avgt       3   4.070 ± 1.865   ms/op
ClientPb.getUser                          avgt       3   4.076 ± 0.762   ms/op
ClientPb.listUser                         avgt       3   4.764 ± 2.322   ms/op
ClientPb.createUser                     sample  235921   4.069 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.169           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.850           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.685           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.905           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.315           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.365           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.436           ms/op
ClientPb.existUser                      sample  239062   4.017 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.327           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.832           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.253           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.329           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.393           ms/op
ClientPb.getUser                        sample  230009   4.174 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.841           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.915           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.734           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.282           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.103           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.901           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.097           ms/op
ClientPb.listUser                       sample  193203   4.967 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.491           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.676           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.535           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.936           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.382           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.835           ms/op
