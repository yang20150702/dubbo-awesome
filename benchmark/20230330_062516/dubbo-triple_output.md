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
# Warmup Iteration   1: 2.084 ops/ms
# Warmup Iteration   2: 5.919 ops/ms
# Warmup Iteration   3: 8.752 ops/ms
Iteration   1: 8.989 ops/ms
Iteration   2: 9.494 ops/ms
Iteration   3: 9.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.408 ±(99.9%) 6.976 ops/ms [Average]
  (min, avg, max) = (8.989, 9.408, 9.739), stdev = 0.382
  CI (99.9%): [2.432, 16.384] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.080 ops/ms
# Warmup Iteration   2: 9.249 ops/ms
# Warmup Iteration   3: 9.632 ops/ms
Iteration   1: 10.105 ops/ms
Iteration   2: 9.979 ops/ms
Iteration   3: 9.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.992 ±(99.9%) 1.961 ops/ms [Average]
  (min, avg, max) = (9.891, 9.992, 10.105), stdev = 0.107
  CI (99.9%): [8.031, 11.953] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.930 ops/ms
# Warmup Iteration   2: 8.439 ops/ms
# Warmup Iteration   3: 9.149 ops/ms
Iteration   1: 9.235 ops/ms
Iteration   2: 9.468 ops/ms
Iteration   3: 9.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.467 ±(99.9%) 4.222 ops/ms [Average]
  (min, avg, max) = (9.235, 9.467, 9.698), stdev = 0.231
  CI (99.9%): [5.245, 13.689] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.753 ops/ms
# Warmup Iteration   2: 6.711 ops/ms
# Warmup Iteration   3: 7.923 ops/ms
Iteration   1: 7.776 ops/ms
Iteration   2: 7.830 ops/ms
Iteration   3: 8.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.938 ±(99.9%) 4.295 ops/ms [Average]
  (min, avg, max) = (7.776, 7.938, 8.208), stdev = 0.235
  CI (99.9%): [3.643, 12.233] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.970 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.639 ±(99.9%) 0.008 ms/op
Iteration   1: 3.443 ±(99.9%) 0.010 ms/op
Iteration   2: 3.528 ±(99.9%) 0.007 ms/op
Iteration   3: 3.519 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.497 ±(99.9%) 0.849 ms/op [Average]
  (min, avg, max) = (3.443, 3.497, 3.528), stdev = 0.047
  CI (99.9%): [2.647, 4.346] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 11.490 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.353 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.146 ±(99.9%) 0.004 ms/op
Iteration   1: 4.070 ±(99.9%) 0.007 ms/op
Iteration   2: 3.824 ±(99.9%) 0.010 ms/op
Iteration   3: 3.764 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.886 ±(99.9%) 2.954 ms/op [Average]
  (min, avg, max) = (3.764, 3.886, 4.070), stdev = 0.162
  CI (99.9%): [0.932, 6.840] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 13.918 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.698 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.007 ms/op
Iteration   1: 3.983 ±(99.9%) 0.006 ms/op
Iteration   2: 3.936 ±(99.9%) 0.008 ms/op
Iteration   3: 4.019 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.979 ±(99.9%) 0.766 ms/op [Average]
  (min, avg, max) = (3.936, 3.979, 4.019), stdev = 0.042
  CI (99.9%): [3.214, 4.745] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 14.128 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.164 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.796 ±(99.9%) 0.006 ms/op
Iteration   1: 4.564 ±(99.9%) 0.012 ms/op
Iteration   2: 4.578 ±(99.9%) 0.014 ms/op
Iteration   3: 4.536 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.560 ±(99.9%) 0.395 ms/op [Average]
  (min, avg, max) = (4.536, 4.560, 4.578), stdev = 0.022
  CI (99.9%): [4.165, 4.955] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.461 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.721 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.272 ±(99.9%) 0.017 ms/op
Iteration   1: 3.937 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.962 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   5.284 ms/op
                 createUser·p0.99:   7.578 ms/op
                 createUser·p0.999:  23.520 ms/op
                 createUser·p0.9999: 32.035 ms/op
                 createUser·p1.00:   32.637 ms/op

Iteration   2: 3.859 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.827 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  25.100 ms/op
                 createUser·p0.9999: 28.672 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   3: 3.914 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.751 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   6.881 ms/op
                 createUser·p0.999:  28.517 ms/op
                 createUser·p0.9999: 33.177 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 245738
  mean =      3.903 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 548 
    [ 2.500,  5.000) = 232866 
    [ 5.000,  7.500) = 10344 
    [ 7.500, 10.000) = 1201 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 73 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.751 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     24.716 ms/op
     p(99.9900) =     32.290 ms/op
     p(99.9990) =     33.893 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.065 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.011 ms/op
Iteration   1: 3.869 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   5.308 ms/op
                 existUser·p0.99:   8.274 ms/op
                 existUser·p0.999:  14.402 ms/op
                 existUser·p0.9999: 24.928 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   2: 3.797 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.663 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.858 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  24.796 ms/op
                 existUser·p0.9999: 27.399 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   3: 3.757 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   6.627 ms/op
                 existUser·p0.999:  10.140 ms/op
                 existUser·p0.9999: 32.997 ms/op
                 existUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252008
  mean =      3.807 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1360 
    [ 2.500,  5.000) = 238648 
    [ 5.000,  7.500) = 9899 
    [ 7.500, 10.000) = 1451 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     14.418 ms/op
     p(99.9900) =     31.936 ms/op
     p(99.9990) =     33.911 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 12.053 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.304 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.020 ms/op
Iteration   1: 3.481 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   8.521 ms/op
                 getUser·p0.999:  18.845 ms/op
                 getUser·p0.9999: 20.513 ms/op
                 getUser·p1.00:   21.201 ms/op

Iteration   2: 3.412 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  20.316 ms/op
                 getUser·p0.9999: 22.901 ms/op
                 getUser·p1.00:   23.921 ms/op

Iteration   3: 3.306 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.552 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.161 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  13.390 ms/op
                 getUser·p0.9999: 33.139 ms/op
                 getUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282371
  mean =      3.398 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6835 
    [ 2.500,  5.000) = 264359 
    [ 5.000,  7.500) = 8933 
    [ 7.500, 10.000) = 1430 
    [10.000, 12.500) = 408 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 147 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     32.400 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.453 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.416 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.361 ±(99.9%) 0.018 ms/op
Iteration   1: 4.241 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   6.210 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  21.329 ms/op
                 listUser·p0.9999: 28.228 ms/op
                 listUser·p1.00:   29.491 ms/op

Iteration   2: 3.869 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.894 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  15.752 ms/op
                 listUser·p0.9999: 17.829 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   3: 4.100 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   8.315 ms/op
                 listUser·p0.999:  16.138 ms/op
                 listUser·p0.9999: 24.917 ms/op
                 listUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236068
  mean =      4.064 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 321 
    [ 2.500,  5.000) = 217265 
    [ 5.000,  7.500) = 15019 
    [ 7.500, 10.000) = 2564 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 220 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.894 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     17.070 ms/op
     p(99.9900) =     26.344 ms/op
     p(99.9990) =     29.209 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.408 ± 6.976  ops/ms
ClientPb.existUser                       thrpt       3   9.992 ± 1.961  ops/ms
ClientPb.getUser                         thrpt       3   9.467 ± 4.222  ops/ms
ClientPb.listUser                        thrpt       3   7.938 ± 4.295  ops/ms
ClientPb.createUser                       avgt       3   3.497 ± 0.849   ms/op
ClientPb.existUser                        avgt       3   3.886 ± 2.954   ms/op
ClientPb.getUser                          avgt       3   3.979 ± 0.766   ms/op
ClientPb.listUser                         avgt       3   4.560 ± 0.395   ms/op
ClientPb.createUser                     sample  245738   3.903 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.751           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.448           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.005           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.086           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.716           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.290           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.275           ms/op
ClientPb.existUser                      sample  252008   3.807 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.296           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.956           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.201           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.418           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.936           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.472           ms/op
ClientPb.getUser                        sample  282371   3.398 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.802           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.127           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.268           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.400           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.554           ms/op
ClientPb.listUser                       sample  236068   4.064 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.894           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.086           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.070           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.344           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.491           ms/op
