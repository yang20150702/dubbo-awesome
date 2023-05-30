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
# Warmup Iteration   1: 2.009 ops/ms
# Warmup Iteration   2: 5.862 ops/ms
# Warmup Iteration   3: 8.536 ops/ms
Iteration   1: 9.235 ops/ms
Iteration   2: 9.446 ops/ms
Iteration   3: 9.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.299 ±(99.9%) 2.331 ops/ms [Average]
  (min, avg, max) = (9.216, 9.299, 9.446), stdev = 0.128
  CI (99.9%): [6.968, 11.629] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.392 ops/ms
# Warmup Iteration   2: 8.996 ops/ms
# Warmup Iteration   3: 9.899 ops/ms
Iteration   1: 9.698 ops/ms
Iteration   2: 10.020 ops/ms
Iteration   3: 9.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.870 ±(99.9%) 2.964 ops/ms [Average]
  (min, avg, max) = (9.698, 9.870, 10.020), stdev = 0.162
  CI (99.9%): [6.906, 12.835] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.922 ops/ms
# Warmup Iteration   2: 8.492 ops/ms
# Warmup Iteration   3: 9.209 ops/ms
Iteration   1: 9.029 ops/ms
Iteration   2: 9.491 ops/ms
Iteration   3: 9.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.347 ±(99.9%) 5.030 ops/ms [Average]
  (min, avg, max) = (9.029, 9.347, 9.521), stdev = 0.276
  CI (99.9%): [4.316, 14.377] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.907 ops/ms
# Warmup Iteration   2: 7.416 ops/ms
# Warmup Iteration   3: 7.954 ops/ms
Iteration   1: 8.127 ops/ms
Iteration   2: 8.174 ops/ms
Iteration   3: 8.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.138 ±(99.9%) 0.575 ops/ms [Average]
  (min, avg, max) = (8.114, 8.138, 8.174), stdev = 0.032
  CI (99.9%): [7.563, 8.713] (assumes normal distribution)


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
# Warmup Iteration   1: 12.295 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.651 ±(99.9%) 0.003 ms/op
Iteration   1: 3.582 ±(99.9%) 0.004 ms/op
Iteration   2: 3.339 ±(99.9%) 0.003 ms/op
Iteration   3: 3.458 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.459 ±(99.9%) 2.223 ms/op [Average]
  (min, avg, max) = (3.339, 3.459, 3.582), stdev = 0.122
  CI (99.9%): [1.237, 5.682] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.286 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.006 ms/op
Iteration   1: 3.182 ±(99.9%) 0.008 ms/op
Iteration   2: 3.195 ±(99.9%) 0.005 ms/op
Iteration   3: 3.198 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.192 ±(99.9%) 0.153 ms/op [Average]
  (min, avg, max) = (3.182, 3.192, 3.198), stdev = 0.008
  CI (99.9%): [3.039, 3.345] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.915 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.463 ±(99.9%) 0.004 ms/op
Iteration   1: 3.436 ±(99.9%) 0.005 ms/op
Iteration   2: 3.330 ±(99.9%) 0.005 ms/op
Iteration   3: 3.374 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.380 ±(99.9%) 0.972 ms/op [Average]
  (min, avg, max) = (3.330, 3.380, 3.436), stdev = 0.053
  CI (99.9%): [2.408, 4.353] (assumes normal distribution)


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
# Warmup Iteration   1: 9.484 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.210 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.008 ms/op
Iteration   1: 3.974 ±(99.9%) 0.009 ms/op
Iteration   2: 3.925 ±(99.9%) 0.008 ms/op
Iteration   3: 3.859 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.919 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (3.859, 3.919, 3.974), stdev = 0.058
  CI (99.9%): [2.865, 4.974] (assumes normal distribution)


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
# Warmup Iteration   1: 9.020 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.008 ms/op
Iteration   1: 3.322 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   6.087 ms/op
                 createUser·p0.999:  17.724 ms/op
                 createUser·p0.9999: 24.490 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   2: 3.365 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.339 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  21.491 ms/op
                 createUser·p0.9999: 25.133 ms/op
                 createUser·p1.00:   26.018 ms/op

Iteration   3: 3.282 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.710 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  16.084 ms/op
                 createUser·p0.9999: 28.246 ms/op
                 createUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288648
  mean =      3.323 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9149 
    [ 2.500,  5.000) = 273682 
    [ 5.000,  7.500) = 4583 
    [ 7.500, 10.000) = 722 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     17.247 ms/op
     p(99.9900) =     27.792 ms/op
     p(99.9990) =     28.618 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 10.111 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.009 ms/op
Iteration   1: 3.492 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  20.367 ms/op
                 existUser·p0.9999: 22.959 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   2: 3.267 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  14.083 ms/op
                 existUser·p0.9999: 25.756 ms/op
                 existUser·p1.00:   26.673 ms/op

Iteration   3: 3.337 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.710 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  8.675 ms/op
                 existUser·p0.9999: 27.581 ms/op
                 existUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285342
  mean =      3.363 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8494 
    [ 2.500,  5.000) = 270230 
    [ 5.000,  7.500) = 5518 
    [ 7.500, 10.000) = 614 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     13.020 ms/op
     p(99.9900) =     26.033 ms/op
     p(99.9990) =     27.820 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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
# Warmup Iteration   1: 9.386 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.009 ms/op
Iteration   1: 3.428 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  19.399 ms/op
                 getUser·p0.9999: 27.907 ms/op
                 getUser·p1.00:   29.458 ms/op

Iteration   2: 3.418 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.399 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.917 ms/op
                 getUser·p0.999:  21.650 ms/op
                 getUser·p0.9999: 29.971 ms/op
                 getUser·p1.00:   30.376 ms/op

Iteration   3: 3.520 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.528 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  21.160 ms/op
                 getUser·p0.9999: 25.575 ms/op
                 getUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277647
  mean =      3.455 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7674 
    [ 2.500,  5.000) = 261970 
    [ 5.000,  7.500) = 6837 
    [ 7.500, 10.000) = 766 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     19.705 ms/op
     p(99.9900) =     28.443 ms/op
     p(99.9990) =     30.056 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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
# Warmup Iteration   1: 11.070 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.094 ±(99.9%) 0.014 ms/op
Iteration   1: 3.926 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.083 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  18.851 ms/op
                 listUser·p0.9999: 24.348 ms/op
                 listUser·p1.00:   25.461 ms/op

Iteration   2: 3.906 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  15.281 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   3: 3.936 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.747 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  14.189 ms/op
                 listUser·p0.9999: 15.546 ms/op
                 listUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244712
  mean =      3.922 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 237838 
    [ 5.000,  7.500) = 5260 
    [ 7.500, 10.000) = 950 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.083 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     15.553 ms/op
     p(99.9900) =     22.727 ms/op
     p(99.9990) =     25.184 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.299 ± 2.331  ops/ms
ClientPb.existUser                       thrpt       3   9.870 ± 2.964  ops/ms
ClientPb.getUser                         thrpt       3   9.347 ± 5.030  ops/ms
ClientPb.listUser                        thrpt       3   8.138 ± 0.575  ops/ms
ClientPb.createUser                       avgt       3   3.459 ± 2.223   ms/op
ClientPb.existUser                        avgt       3   3.192 ± 0.153   ms/op
ClientPb.getUser                          avgt       3   3.380 ± 0.972   ms/op
ClientPb.listUser                         avgt       3   3.919 ± 1.054   ms/op
ClientPb.createUser                     sample  288648   3.323 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.339           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.690           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.743           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.247           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.792           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.179           ms/op
ClientPb.existUser                      sample  285342   3.363 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.268           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.887           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.358           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.792           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.020           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.033           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.312           ms/op
ClientPb.getUser                        sample  277647   3.455 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.399           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.705           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.443           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.376           ms/op
ClientPb.listUser                       sample  244712   3.922 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.083           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.783           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.553           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.727           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.461           ms/op
