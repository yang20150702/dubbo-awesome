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
# Warmup Iteration   1: 1.745 ops/ms
# Warmup Iteration   2: 3.569 ops/ms
# Warmup Iteration   3: 6.811 ops/ms
Iteration   1: 6.986 ops/ms
Iteration   2: 8.004 ops/ms
Iteration   3: 7.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.642 ±(99.9%) 10.384 ops/ms [Average]
  (min, avg, max) = (6.986, 7.642, 8.004), stdev = 0.569
  CI (99.9%): [≈ 0, 18.026] (assumes normal distribution)


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
# Warmup Iteration   1: 2.017 ops/ms
# Warmup Iteration   2: 6.412 ops/ms
# Warmup Iteration   3: 7.896 ops/ms
Iteration   1: 7.965 ops/ms
Iteration   2: 8.115 ops/ms
Iteration   3: 8.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.103 ±(99.9%) 2.430 ops/ms [Average]
  (min, avg, max) = (7.965, 8.103, 8.230), stdev = 0.133
  CI (99.9%): [5.674, 10.533] (assumes normal distribution)


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
# Warmup Iteration   1: 2.280 ops/ms
# Warmup Iteration   2: 6.187 ops/ms
# Warmup Iteration   3: 7.688 ops/ms
Iteration   1: 7.673 ops/ms
Iteration   2: 7.520 ops/ms
Iteration   3: 7.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.537 ±(99.9%) 2.344 ops/ms [Average]
  (min, avg, max) = (7.417, 7.537, 7.673), stdev = 0.128
  CI (99.9%): [5.193, 9.880] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.899 ops/ms
# Warmup Iteration   2: 4.524 ops/ms
# Warmup Iteration   3: 6.388 ops/ms
Iteration   1: 6.408 ops/ms
Iteration   2: 6.108 ops/ms
Iteration   3: 6.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.289 ±(99.9%) 2.898 ops/ms [Average]
  (min, avg, max) = (6.108, 6.289, 6.408), stdev = 0.159
  CI (99.9%): [3.391, 9.187] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.835 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.856 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.513 ±(99.9%) 0.008 ms/op
Iteration   1: 4.292 ±(99.9%) 0.005 ms/op
Iteration   2: 4.308 ±(99.9%) 0.009 ms/op
Iteration   3: 4.265 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.288 ±(99.9%) 0.391 ms/op [Average]
  (min, avg, max) = (4.265, 4.288, 4.308), stdev = 0.021
  CI (99.9%): [3.897, 4.679] (assumes normal distribution)


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
# Warmup Iteration   1: 13.054 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.019 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.242 ±(99.9%) 0.008 ms/op
Iteration   1: 4.080 ±(99.9%) 0.004 ms/op
Iteration   2: 4.074 ±(99.9%) 0.005 ms/op
Iteration   3: 4.259 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.138 ±(99.9%) 1.919 ms/op [Average]
  (min, avg, max) = (4.074, 4.138, 4.259), stdev = 0.105
  CI (99.9%): [2.219, 6.056] (assumes normal distribution)


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
# Warmup Iteration   1: 13.246 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.102 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.415 ±(99.9%) 0.011 ms/op
Iteration   1: 3.972 ±(99.9%) 0.013 ms/op
Iteration   2: 4.075 ±(99.9%) 0.008 ms/op
Iteration   3: 3.969 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.006 ±(99.9%) 1.106 ms/op [Average]
  (min, avg, max) = (3.969, 4.006, 4.075), stdev = 0.061
  CI (99.9%): [2.899, 5.112] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.000 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.879 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.515 ±(99.9%) 0.009 ms/op
Iteration   1: 4.997 ±(99.9%) 0.009 ms/op
Iteration   2: 4.820 ±(99.9%) 0.009 ms/op
Iteration   3: 4.923 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.913 ±(99.9%) 1.628 ms/op [Average]
  (min, avg, max) = (4.820, 4.913, 4.997), stdev = 0.089
  CI (99.9%): [3.286, 6.541] (assumes normal distribution)


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
# Warmup Iteration   1: 14.155 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 5.457 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.694 ±(99.9%) 0.020 ms/op
Iteration   1: 4.080 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.692 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   8.118 ms/op
                 createUser·p0.999:  14.443 ms/op
                 createUser·p0.9999: 26.721 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   2: 4.245 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.593 ms/op
                 createUser·p0.50:   3.965 ms/op
                 createUser·p0.90:   5.341 ms/op
                 createUser·p0.95:   6.193 ms/op
                 createUser·p0.99:   8.536 ms/op
                 createUser·p0.999:  26.302 ms/op
                 createUser·p0.9999: 29.882 ms/op
                 createUser·p1.00:   30.179 ms/op

Iteration   3: 4.122 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.663 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.390 ms/op
                 createUser·p0.99:   7.733 ms/op
                 createUser·p0.999:  21.987 ms/op
                 createUser·p0.9999: 31.382 ms/op
                 createUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 231473
  mean =      4.148 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 305 
    [ 2.500,  5.000) = 209711 
    [ 5.000,  7.500) = 17912 
    [ 7.500, 10.000) = 2513 
    [10.000, 12.500) = 513 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 126 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.593 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      8.176 ms/op
     p(99.9000) =     24.921 ms/op
     p(99.9900) =     30.664 ms/op
     p(99.9990) =     31.821 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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
# Warmup Iteration   1: 12.760 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 4.961 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.478 ±(99.9%) 0.019 ms/op
Iteration   1: 4.125 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.520 ms/op
                 existUser·p0.50:   3.912 ms/op
                 existUser·p0.90:   4.874 ms/op
                 existUser·p0.95:   5.710 ms/op
                 existUser·p0.99:   8.246 ms/op
                 existUser·p0.999:  14.513 ms/op
                 existUser·p0.9999: 27.959 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   2: 4.086 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.679 ms/op
                 existUser·p0.50:   3.903 ms/op
                 existUser·p0.90:   4.874 ms/op
                 existUser·p0.95:   5.554 ms/op
                 existUser·p0.99:   7.578 ms/op
                 existUser·p0.999:  11.059 ms/op
                 existUser·p0.9999: 28.329 ms/op
                 existUser·p1.00:   29.786 ms/op

Iteration   3: 4.395 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.436 ms/op
                 existUser·p0.50:   4.030 ms/op
                 existUser·p0.90:   5.521 ms/op
                 existUser·p0.95:   6.840 ms/op
                 existUser·p0.99:   10.387 ms/op
                 existUser·p0.999:  22.512 ms/op
                 existUser·p0.9999: 37.093 ms/op
                 existUser·p1.00:   37.487 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 228615
  mean =      4.198 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 224 
    [ 2.500,  5.000) = 204072 
    [ 5.000,  7.500) = 19764 
    [ 7.500, 10.000) = 3236 
    [10.000, 12.500) = 897 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.436 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      6.029 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     35.988 ms/op
     p(99.9990) =     37.487 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


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
# Warmup Iteration   1: 15.553 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 5.733 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.685 ±(99.9%) 0.020 ms/op
Iteration   1: 4.668 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.757 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   6.136 ms/op
                 getUser·p0.95:   7.627 ms/op
                 getUser·p0.99:   11.713 ms/op
                 getUser·p0.999:  20.218 ms/op
                 getUser·p0.9999: 28.056 ms/op
                 getUser·p1.00:   28.738 ms/op

Iteration   2: 4.295 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.364 ms/op
                 getUser·p0.50:   4.035 ms/op
                 getUser·p0.90:   5.120 ms/op
                 getUser·p0.95:   6.095 ms/op
                 getUser·p0.99:   8.651 ms/op
                 getUser·p0.999:  12.712 ms/op
                 getUser·p0.9999: 29.738 ms/op
                 getUser·p1.00:   32.408 ms/op

Iteration   3: 4.170 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.698 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   8.266 ms/op
                 getUser·p0.999:  19.202 ms/op
                 getUser·p0.9999: 32.656 ms/op
                 getUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 219864
  mean =      4.367 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 192522 
    [ 5.000,  7.500) = 20884 
    [ 7.500, 10.000) = 4530 
    [10.000, 12.500) = 1187 
    [12.500, 15.000) = 357 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 103 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      4.055 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      6.562 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     30.410 ms/op
     p(99.9990) =     34.131 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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
# Warmup Iteration   1: 16.762 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 6.224 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.328 ±(99.9%) 0.021 ms/op
Iteration   1: 5.254 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.896 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   6.488 ms/op
                 listUser·p0.95:   7.889 ms/op
                 listUser·p0.99:   10.230 ms/op
                 listUser·p0.999:  24.674 ms/op
                 listUser·p0.9999: 26.965 ms/op
                 listUser·p1.00:   27.853 ms/op

Iteration   2: 5.067 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.589 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   5.865 ms/op
                 listUser·p0.95:   7.119 ms/op
                 listUser·p0.99:   9.585 ms/op
                 listUser·p0.999:  20.967 ms/op
                 listUser·p0.9999: 31.799 ms/op
                 listUser·p1.00:   32.834 ms/op

Iteration   3: 4.860 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.834 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  17.800 ms/op
                 listUser·p0.9999: 21.668 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 189797
  mean =      5.055 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 128221 
    [ 5.000,  7.500) = 53049 
    [ 7.500, 10.000) = 6943 
    [10.000, 12.500) = 847 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.896 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      5.865 ms/op
     p(95.0000) =      7.234 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     21.404 ms/op
     p(99.9900) =     28.083 ms/op
     p(99.9990) =     32.745 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.642 ± 10.384  ops/ms
ClientPb.existUser                       thrpt       3   8.103 ±  2.430  ops/ms
ClientPb.getUser                         thrpt       3   7.537 ±  2.344  ops/ms
ClientPb.listUser                        thrpt       3   6.289 ±  2.898  ops/ms
ClientPb.createUser                       avgt       3   4.288 ±  0.391   ms/op
ClientPb.existUser                        avgt       3   4.138 ±  1.919   ms/op
ClientPb.getUser                          avgt       3   4.006 ±  1.106   ms/op
ClientPb.listUser                         avgt       3   4.913 ±  1.628   ms/op
ClientPb.createUser                     sample  231473   4.148 ±  0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.593            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.928            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.923            ms/op
ClientPb.createUser:createUser·p0.95    sample           5.874            ms/op
ClientPb.createUser:createUser·p0.99    sample           8.176            ms/op
ClientPb.createUser:createUser·p0.999   sample          24.921            ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.664            ms/op
ClientPb.createUser:createUser·p1.00    sample          32.047            ms/op
ClientPb.existUser                      sample  228615   4.198 ±  0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.436            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.936            ms/op
ClientPb.existUser:existUser·p0.90      sample           5.079            ms/op
ClientPb.existUser:existUser·p0.95      sample           6.029            ms/op
ClientPb.existUser:existUser·p0.99      sample           8.831            ms/op
ClientPb.existUser:existUser·p0.999     sample          20.709            ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.988            ms/op
ClientPb.existUser:existUser·p1.00      sample          37.487            ms/op
ClientPb.getUser                        sample  219864   4.367 ±  0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.364            ms/op
ClientPb.getUser:getUser·p0.50          sample           4.055            ms/op
ClientPb.getUser:getUser·p0.90          sample           5.251            ms/op
ClientPb.getUser:getUser·p0.95          sample           6.562            ms/op
ClientPb.getUser:getUser·p0.99          sample           9.585            ms/op
ClientPb.getUser:getUser·p0.999         sample          19.202            ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.410            ms/op
ClientPb.getUser:getUser·p1.00          sample          34.341            ms/op
ClientPb.listUser                       sample  189797   5.055 ±  0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.896            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.760            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.865            ms/op
ClientPb.listUser:listUser·p0.95        sample           7.234            ms/op
ClientPb.listUser:listUser·p0.99        sample           9.732            ms/op
ClientPb.listUser:listUser·p0.999       sample          21.404            ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.083            ms/op
ClientPb.listUser:listUser·p1.00        sample          32.834            ms/op
