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
# Warmup Iteration   1: 1.079 ops/ms
# Warmup Iteration   2: 2.281 ops/ms
# Warmup Iteration   3: 4.885 ops/ms
Iteration   1: 5.344 ops/ms
Iteration   2: 5.603 ops/ms
Iteration   3: 5.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.463 ±(99.9%) 2.381 ops/ms [Average]
  (min, avg, max) = (5.344, 5.463, 5.603), stdev = 0.131
  CI (99.9%): [3.082, 7.844] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.579 ops/ms
# Warmup Iteration   2: 5.079 ops/ms
# Warmup Iteration   3: 5.883 ops/ms
Iteration   1: 5.695 ops/ms
Iteration   2: 5.813 ops/ms
Iteration   3: 5.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.832 ±(99.9%) 2.684 ops/ms [Average]
  (min, avg, max) = (5.695, 5.832, 5.987), stdev = 0.147
  CI (99.9%): [3.148, 8.515] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.351 ops/ms
# Warmup Iteration   2: 3.927 ops/ms
# Warmup Iteration   3: 5.516 ops/ms
Iteration   1: 5.383 ops/ms
Iteration   2: 5.602 ops/ms
Iteration   3: 5.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.596 ±(99.9%) 3.842 ops/ms [Average]
  (min, avg, max) = (5.383, 5.596, 5.804), stdev = 0.211
  CI (99.9%): [1.754, 9.439] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.407 ops/ms
# Warmup Iteration   2: 3.960 ops/ms
# Warmup Iteration   3: 4.931 ops/ms
Iteration   1: 4.813 ops/ms
Iteration   2: 4.978 ops/ms
Iteration   3: 4.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.870 ±(99.9%) 1.711 ops/ms [Average]
  (min, avg, max) = (4.813, 4.870, 4.978), stdev = 0.094
  CI (99.9%): [3.159, 6.580] (assumes normal distribution)


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
# Warmup Iteration   1: 20.172 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 6.913 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.986 ±(99.9%) 0.011 ms/op
Iteration   1: 5.328 ±(99.9%) 0.025 ms/op
Iteration   2: 5.428 ±(99.9%) 0.018 ms/op
Iteration   3: 5.581 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.446 ±(99.9%) 2.332 ms/op [Average]
  (min, avg, max) = (5.328, 5.446, 5.581), stdev = 0.128
  CI (99.9%): [3.114, 7.778] (assumes normal distribution)


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
# Warmup Iteration   1: 19.070 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 6.963 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.763 ±(99.9%) 0.015 ms/op
Iteration   1: 5.619 ±(99.9%) 0.013 ms/op
Iteration   2: 5.505 ±(99.9%) 0.012 ms/op
Iteration   3: 5.298 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.474 ±(99.9%) 2.967 ms/op [Average]
  (min, avg, max) = (5.298, 5.474, 5.619), stdev = 0.163
  CI (99.9%): [2.507, 8.441] (assumes normal distribution)


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
# Warmup Iteration   1: 19.840 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 7.083 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.041 ±(99.9%) 0.016 ms/op
Iteration   1: 5.812 ±(99.9%) 0.017 ms/op
Iteration   2: 5.629 ±(99.9%) 0.020 ms/op
Iteration   3: 5.763 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.734 ±(99.9%) 1.729 ms/op [Average]
  (min, avg, max) = (5.629, 5.734, 5.812), stdev = 0.095
  CI (99.9%): [4.005, 7.464] (assumes normal distribution)


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
# Warmup Iteration   1: 18.574 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 8.938 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.565 ±(99.9%) 0.012 ms/op
Iteration   1: 6.779 ±(99.9%) 0.015 ms/op
Iteration   2: 6.256 ±(99.9%) 0.030 ms/op
Iteration   3: 6.811 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.615 ±(99.9%) 5.690 ms/op [Average]
  (min, avg, max) = (6.256, 6.615, 6.811), stdev = 0.312
  CI (99.9%): [0.926, 12.305] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.312 ±(99.9%) 0.344 ms/op
# Warmup Iteration   2: 7.848 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 5.906 ±(99.9%) 0.025 ms/op
Iteration   1: 5.684 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.541 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   7.447 ms/op
                 createUser·p0.95:   8.471 ms/op
                 createUser·p0.99:   10.863 ms/op
                 createUser·p0.999:  26.719 ms/op
                 createUser·p0.9999: 30.966 ms/op
                 createUser·p1.00:   33.554 ms/op

Iteration   2: 5.521 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.392 ms/op
                 createUser·p0.50:   5.112 ms/op
                 createUser·p0.90:   6.857 ms/op
                 createUser·p0.95:   8.036 ms/op
                 createUser·p0.99:   10.886 ms/op
                 createUser·p0.999:  25.989 ms/op
                 createUser·p0.9999: 40.908 ms/op
                 createUser·p1.00:   42.336 ms/op

Iteration   3: 5.682 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.507 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   7.184 ms/op
                 createUser·p0.95:   8.167 ms/op
                 createUser·p0.99:   11.567 ms/op
                 createUser·p0.999:  27.197 ms/op
                 createUser·p0.9999: 35.610 ms/op
                 createUser·p1.00:   45.351 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170555
  mean =      5.628 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 66204 
    [ 5.000, 10.000) = 101446 
    [10.000, 15.000) = 2472 
    [15.000, 20.000) = 181 
    [20.000, 25.000) = 54 
    [25.000, 30.000) = 118 
    [30.000, 35.000) = 25 
    [35.000, 40.000) = 47 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      7.152 ms/op
     p(95.0000) =      8.249 ms/op
     p(99.0000) =     11.076 ms/op
     p(99.9000) =     26.618 ms/op
     p(99.9900) =     35.713 ms/op
     p(99.9990) =     44.426 ms/op
     p(99.9999) =     45.351 ms/op
    p(100.0000) =     45.351 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.597 ±(99.9%) 0.293 ms/op
# Warmup Iteration   2: 7.117 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.537 ±(99.9%) 0.022 ms/op
Iteration   1: 5.481 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.216 ms/op
                 existUser·p0.50:   5.087 ms/op
                 existUser·p0.90:   7.004 ms/op
                 existUser·p0.95:   8.282 ms/op
                 existUser·p0.99:   10.961 ms/op
                 existUser·p0.999:  23.028 ms/op
                 existUser·p0.9999: 28.508 ms/op
                 existUser·p1.00:   29.000 ms/op

Iteration   2: 5.485 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.482 ms/op
                 existUser·p0.50:   5.145 ms/op
                 existUser·p0.90:   6.843 ms/op
                 existUser·p0.95:   8.103 ms/op
                 existUser·p0.99:   10.748 ms/op
                 existUser·p0.999:  25.713 ms/op
                 existUser·p0.9999: 31.922 ms/op
                 existUser·p1.00:   32.244 ms/op

Iteration   3: 5.468 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.519 ms/op
                 existUser·p0.50:   5.153 ms/op
                 existUser·p0.90:   6.783 ms/op
                 existUser·p0.95:   8.132 ms/op
                 existUser·p0.99:   10.727 ms/op
                 existUser·p0.999:  14.640 ms/op
                 existUser·p0.9999: 31.036 ms/op
                 existUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 175041
  mean =      5.478 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 71361 
    [ 5.000,  7.500) = 91170 
    [ 7.500, 10.000) = 9808 
    [10.000, 12.500) = 1921 
    [12.500, 15.000) = 434 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.216 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.871 ms/op
     p(95.0000) =      8.176 ms/op
     p(99.0000) =     10.797 ms/op
     p(99.9000) =     19.987 ms/op
     p(99.9900) =     31.392 ms/op
     p(99.9990) =     32.096 ms/op
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
# Warmup Iteration   1: 18.056 ±(99.9%) 0.292 ms/op
# Warmup Iteration   2: 6.372 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.626 ±(99.9%) 0.021 ms/op
Iteration   1: 5.771 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.630 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   7.324 ms/op
                 getUser·p0.95:   8.880 ms/op
                 getUser·p0.99:   12.534 ms/op
                 getUser·p0.999:  26.673 ms/op
                 getUser·p0.9999: 35.324 ms/op
                 getUser·p1.00:   35.652 ms/op

Iteration   2: 5.757 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.724 ms/op
                 getUser·p0.50:   5.366 ms/op
                 getUser·p0.90:   7.168 ms/op
                 getUser·p0.95:   8.372 ms/op
                 getUser·p0.99:   12.321 ms/op
                 getUser·p0.999:  26.870 ms/op
                 getUser·p0.9999: 33.528 ms/op
                 getUser·p1.00:   33.882 ms/op

Iteration   3: 5.576 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.913 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   7.004 ms/op
                 getUser·p0.95:   7.963 ms/op
                 getUser·p0.99:   10.043 ms/op
                 getUser·p0.999:  14.191 ms/op
                 getUser·p0.9999: 28.828 ms/op
                 getUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168503
  mean =      5.700 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 54448 
    [ 5.000,  7.500) = 100302 
    [ 7.500, 10.000) = 10353 
    [10.000, 12.500) = 2166 
    [12.500, 15.000) = 720 
    [15.000, 17.500) = 261 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.913 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      7.135 ms/op
     p(95.0000) =      8.356 ms/op
     p(99.0000) =     11.698 ms/op
     p(99.9000) =     25.165 ms/op
     p(99.9900) =     34.220 ms/op
     p(99.9990) =     35.562 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 21.163 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 8.617 ±(99.9%) 0.066 ms/op
# Warmup Iteration   3: 6.873 ±(99.9%) 0.030 ms/op
Iteration   1: 6.706 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.375 ms/op
                 listUser·p0.50:   6.316 ms/op
                 listUser·p0.90:   8.348 ms/op
                 listUser·p0.95:   9.552 ms/op
                 listUser·p0.99:   12.878 ms/op
                 listUser·p0.999:  27.454 ms/op
                 listUser·p0.9999: 36.018 ms/op
                 listUser·p1.00:   37.290 ms/op

Iteration   2: 6.516 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.318 ms/op
                 listUser·p0.50:   6.095 ms/op
                 listUser·p0.90:   8.110 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   11.955 ms/op
                 listUser·p0.999:  29.982 ms/op
                 listUser·p0.9999: 36.641 ms/op
                 listUser·p1.00:   37.683 ms/op

Iteration   3: 6.576 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.166 ms/op
                 listUser·p0.50:   6.250 ms/op
                 listUser·p0.90:   7.979 ms/op
                 listUser·p0.95:   9.110 ms/op
                 listUser·p0.99:   11.698 ms/op
                 listUser·p0.999:  26.847 ms/op
                 listUser·p0.9999: 30.811 ms/op
                 listUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145439
  mean =      6.598 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 3967 
    [ 5.000,  7.500) = 118563 
    [ 7.500, 10.000) = 18241 
    [10.000, 12.500) = 3375 
    [12.500, 15.000) = 734 
    [15.000, 17.500) = 214 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      3.166 ms/op
     p(50.0000) =      6.226 ms/op
     p(90.0000) =      8.159 ms/op
     p(95.0000) =      9.273 ms/op
     p(99.0000) =     12.239 ms/op
     p(99.9000) =     28.312 ms/op
     p(99.9900) =     35.378 ms/op
     p(99.9990) =     37.624 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.463 ± 2.381  ops/ms
ClientPb.existUser                       thrpt       3   5.832 ± 2.684  ops/ms
ClientPb.getUser                         thrpt       3   5.596 ± 3.842  ops/ms
ClientPb.listUser                        thrpt       3   4.870 ± 1.711  ops/ms
ClientPb.createUser                       avgt       3   5.446 ± 2.332   ms/op
ClientPb.existUser                        avgt       3   5.474 ± 2.967   ms/op
ClientPb.getUser                          avgt       3   5.734 ± 1.729   ms/op
ClientPb.listUser                         avgt       3   6.615 ± 5.690   ms/op
ClientPb.createUser                     sample  170555   5.628 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.541           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.194           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.152           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.249           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.076           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.618           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.713           ms/op
ClientPb.createUser:createUser·p1.00    sample          45.351           ms/op
ClientPb.existUser                      sample  175041   5.478 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.216           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.136           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.871           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.176           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.797           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.987           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.392           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.244           ms/op
ClientPb.getUser                        sample  168503   5.700 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.913           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.325           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.135           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.356           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.698           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.165           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.220           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.652           ms/op
ClientPb.listUser                       sample  145439   6.598 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           3.166           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.226           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.159           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.273           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.239           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.312           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.378           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.683           ms/op
