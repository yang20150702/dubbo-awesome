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
# Warmup Iteration   1: 2.175 ops/ms
# Warmup Iteration   2: 5.225 ops/ms
# Warmup Iteration   3: 8.764 ops/ms
Iteration   1: 9.282 ops/ms
Iteration   2: 9.403 ops/ms
Iteration   3: 9.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.418 ±(99.9%) 2.619 ops/ms [Average]
  (min, avg, max) = (9.282, 9.418, 9.568), stdev = 0.144
  CI (99.9%): [6.798, 12.037] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.441 ops/ms
# Warmup Iteration   2: 8.599 ops/ms
# Warmup Iteration   3: 9.780 ops/ms
Iteration   1: 9.552 ops/ms
Iteration   2: 9.860 ops/ms
Iteration   3: 9.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.799 ±(99.9%) 4.065 ops/ms [Average]
  (min, avg, max) = (9.552, 9.799, 9.984), stdev = 0.223
  CI (99.9%): [5.734, 13.863] (assumes normal distribution)


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
# Warmup Iteration   1: 2.765 ops/ms
# Warmup Iteration   2: 7.750 ops/ms
# Warmup Iteration   3: 8.967 ops/ms
Iteration   1: 9.355 ops/ms
Iteration   2: 9.242 ops/ms
Iteration   3: 9.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.402 ±(99.9%) 3.440 ops/ms [Average]
  (min, avg, max) = (9.242, 9.402, 9.610), stdev = 0.189
  CI (99.9%): [5.963, 12.842] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.874 ops/ms
# Warmup Iteration   2: 7.059 ops/ms
# Warmup Iteration   3: 7.370 ops/ms
Iteration   1: 8.087 ops/ms
Iteration   2: 8.292 ops/ms
Iteration   3: 7.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.122 ±(99.9%) 2.821 ops/ms [Average]
  (min, avg, max) = (7.988, 8.122, 8.292), stdev = 0.155
  CI (99.9%): [5.301, 10.944] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.591 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.005 ms/op
Iteration   1: 3.396 ±(99.9%) 0.008 ms/op
Iteration   2: 3.373 ±(99.9%) 0.007 ms/op
Iteration   3: 3.342 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.370 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (3.342, 3.370, 3.396), stdev = 0.028
  CI (99.9%): [2.867, 3.873] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.895 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.005 ms/op
Iteration   1: 3.338 ±(99.9%) 0.006 ms/op
Iteration   2: 3.440 ±(99.9%) 0.004 ms/op
Iteration   3: 3.231 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.336 ±(99.9%) 1.904 ms/op [Average]
  (min, avg, max) = (3.231, 3.336, 3.440), stdev = 0.104
  CI (99.9%): [1.432, 5.241] (assumes normal distribution)


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
# Warmup Iteration   1: 8.983 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.005 ms/op
Iteration   1: 3.387 ±(99.9%) 0.005 ms/op
Iteration   2: 3.338 ±(99.9%) 0.008 ms/op
Iteration   3: 3.392 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.373 ±(99.9%) 0.548 ms/op [Average]
  (min, avg, max) = (3.338, 3.373, 3.392), stdev = 0.030
  CI (99.9%): [2.825, 3.921] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.425 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.251 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.011 ms/op
Iteration   1: 3.935 ±(99.9%) 0.009 ms/op
Iteration   2: 3.927 ±(99.9%) 0.008 ms/op
Iteration   3: 3.955 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.939 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (3.927, 3.939, 3.955), stdev = 0.015
  CI (99.9%): [3.672, 4.205] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.158 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 3.929 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.011 ms/op
Iteration   1: 3.610 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.642 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.760 ms/op
                 createUser·p0.95:   5.841 ms/op
                 createUser·p0.99:   7.234 ms/op
                 createUser·p0.999:  10.960 ms/op
                 createUser·p0.9999: 23.790 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   2: 3.316 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.485 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  19.835 ms/op
                 createUser·p0.9999: 25.068 ms/op
                 createUser·p1.00:   25.952 ms/op

Iteration   3: 3.430 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.657 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.196 ms/op
                 createUser·p0.999:  22.670 ms/op
                 createUser·p0.9999: 30.027 ms/op
                 createUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278177
  mean =      3.448 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7967 
    [ 2.500,  5.000) = 257753 
    [ 5.000,  7.500) = 10965 
    [ 7.500, 10.000) = 977 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 154 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.485 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     16.244 ms/op
     p(99.9900) =     29.307 ms/op
     p(99.9990) =     30.430 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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
# Warmup Iteration   1: 8.151 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.453 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.010 ms/op
Iteration   1: 3.196 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.239 ms/op
                 existUser·p0.999:  10.255 ms/op
                 existUser·p0.9999: 23.986 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   2: 3.163 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.333 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  9.044 ms/op
                 existUser·p0.9999: 29.832 ms/op
                 existUser·p1.00:   32.244 ms/op

Iteration   3: 3.350 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.731 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  21.119 ms/op
                 existUser·p0.9999: 29.029 ms/op
                 existUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296875
  mean =      3.234 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15296 
    [ 2.500,  5.000) = 276772 
    [ 5.000,  7.500) = 4302 
    [ 7.500, 10.000) = 213 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      9.945 ms/op
     p(99.9900) =     29.108 ms/op
     p(99.9990) =     30.192 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 9.424 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.010 ms/op
Iteration   1: 3.312 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.831 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  19.697 ms/op
                 getUser·p0.9999: 23.462 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   2: 3.303 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.831 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   5.071 ms/op
                 getUser·p0.999:  14.734 ms/op
                 getUser·p0.9999: 35.389 ms/op
                 getUser·p1.00:   38.076 ms/op

Iteration   3: 3.397 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  17.264 ms/op
                 getUser·p0.9999: 26.234 ms/op
                 getUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287427
  mean =      3.337 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7837 
    [ 2.500,  5.000) = 274470 
    [ 5.000,  7.500) = 3948 
    [ 7.500, 10.000) = 697 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     18.074 ms/op
     p(99.9900) =     33.172 ms/op
     p(99.9990) =     35.725 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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
# Warmup Iteration   1: 10.515 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.374 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.013 ms/op
Iteration   1: 3.968 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  20.192 ms/op
                 listUser·p0.9999: 24.084 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   2: 4.109 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  16.564 ms/op
                 listUser·p0.9999: 18.882 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   3: 4.033 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  16.230 ms/op
                 listUser·p0.9999: 21.070 ms/op
                 listUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237775
  mean =      4.036 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 227327 
    [ 5.000,  7.500) = 7984 
    [ 7.500, 10.000) = 1575 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 237 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     23.076 ms/op
     p(99.9990) =     24.673 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.418 ± 2.619  ops/ms
ClientPb.existUser                       thrpt       3   9.799 ± 4.065  ops/ms
ClientPb.getUser                         thrpt       3   9.402 ± 3.440  ops/ms
ClientPb.listUser                        thrpt       3   8.122 ± 2.821  ops/ms
ClientPb.createUser                       avgt       3   3.370 ± 0.503   ms/op
ClientPb.existUser                        avgt       3   3.336 ± 1.904   ms/op
ClientPb.getUser                          avgt       3   3.373 ± 0.548   ms/op
ClientPb.listUser                         avgt       3   3.939 ± 0.266   ms/op
ClientPb.createUser                     sample  278177   3.448 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.485           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.866           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.619           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.244           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.307           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.573           ms/op
ClientPb.existUser                      sample  296875   3.234 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.333           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.945           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.108           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.244           ms/op
ClientPb.getUser                        sample  287427   3.337 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.239           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.654           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.800           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.074           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.172           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.076           ms/op
ClientPb.listUser                       sample  237775   4.036 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.384           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.545           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.876           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.076           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.477           ms/op
