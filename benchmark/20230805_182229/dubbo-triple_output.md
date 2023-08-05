# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.038 ops/ms
# Warmup Iteration   2: 4.876 ops/ms
# Warmup Iteration   3: 8.204 ops/ms
Iteration   1: 8.774 ops/ms
Iteration   2: 9.150 ops/ms
Iteration   3: 9.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.068 ±(99.9%) 4.786 ops/ms [Average]
  (min, avg, max) = (8.774, 9.068, 9.279), stdev = 0.262
  CI (99.9%): [4.282, 13.854] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.939 ops/ms
# Warmup Iteration   2: 8.667 ops/ms
# Warmup Iteration   3: 9.338 ops/ms
Iteration   1: 9.435 ops/ms
Iteration   2: 9.787 ops/ms
Iteration   3: 9.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.618 ±(99.9%) 3.223 ops/ms [Average]
  (min, avg, max) = (9.435, 9.618, 9.787), stdev = 0.177
  CI (99.9%): [6.395, 12.840] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.824 ops/ms
# Warmup Iteration   2: 8.519 ops/ms
# Warmup Iteration   3: 8.904 ops/ms
Iteration   1: 9.163 ops/ms
Iteration   2: 9.474 ops/ms
Iteration   3: 9.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.300 ±(99.9%) 2.897 ops/ms [Average]
  (min, avg, max) = (9.163, 9.300, 9.474), stdev = 0.159
  CI (99.9%): [6.404, 12.197] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.126 ops/ms
# Warmup Iteration   2: 7.136 ops/ms
# Warmup Iteration   3: 7.800 ops/ms
Iteration   1: 7.905 ops/ms
Iteration   2: 8.045 ops/ms
Iteration   3: 7.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.926 ±(99.9%) 2.001 ops/ms [Average]
  (min, avg, max) = (7.828, 7.926, 8.045), stdev = 0.110
  CI (99.9%): [5.926, 9.927] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.961 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.903 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.005 ms/op
Iteration   1: 3.512 ±(99.9%) 0.008 ms/op
Iteration   2: 3.457 ±(99.9%) 0.013 ms/op
Iteration   3: 3.489 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.486 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (3.457, 3.486, 3.512), stdev = 0.028
  CI (99.9%): [2.981, 3.992] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.844 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.007 ms/op
Iteration   1: 3.203 ±(99.9%) 0.007 ms/op
Iteration   2: 3.271 ±(99.9%) 0.005 ms/op
Iteration   3: 3.269 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.248 ±(99.9%) 0.711 ms/op [Average]
  (min, avg, max) = (3.203, 3.248, 3.271), stdev = 0.039
  CI (99.9%): [2.537, 3.958] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.850 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.691 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.572 ±(99.9%) 0.007 ms/op
Iteration   1: 3.604 ±(99.9%) 0.004 ms/op
Iteration   2: 3.477 ±(99.9%) 0.007 ms/op
Iteration   3: 3.443 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.508 ±(99.9%) 1.545 ms/op [Average]
  (min, avg, max) = (3.443, 3.508, 3.604), stdev = 0.085
  CI (99.9%): [1.963, 5.053] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.918 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.414 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.005 ms/op
Iteration   1: 3.977 ±(99.9%) 0.013 ms/op
Iteration   2: 4.010 ±(99.9%) 0.010 ms/op
Iteration   3: 4.048 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.012 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.977, 4.012, 4.048), stdev = 0.035
  CI (99.9%): [3.368, 4.655] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.328 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.349 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.776 ±(99.9%) 0.014 ms/op
Iteration   1: 3.513 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   7.119 ms/op
                 createUser·p0.999:  20.447 ms/op
                 createUser·p0.9999: 22.737 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   2: 3.414 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.602 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  21.932 ms/op
                 createUser·p0.9999: 29.610 ms/op
                 createUser·p1.00:   31.523 ms/op

Iteration   3: 3.449 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  23.331 ms/op
                 createUser·p0.9999: 27.754 ms/op
                 createUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277484
  mean =      3.458 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12366 
    [ 2.500,  5.000) = 255973 
    [ 5.000,  7.500) = 7591 
    [ 7.500, 10.000) = 1056 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     20.612 ms/op
     p(99.9900) =     28.312 ms/op
     p(99.9990) =     30.365 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.519 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.732 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.009 ms/op
Iteration   1: 3.355 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  19.857 ms/op
                 existUser·p0.9999: 22.036 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   2: 3.586 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   6.707 ms/op
                 existUser·p0.999:  22.144 ms/op
                 existUser·p0.9999: 28.448 ms/op
                 existUser·p1.00:   29.000 ms/op

Iteration   3: 3.290 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.210 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  11.775 ms/op
                 existUser·p0.9999: 25.756 ms/op
                 existUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281840
  mean =      3.406 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10511 
    [ 2.500,  5.000) = 263994 
    [ 5.000,  7.500) = 6107 
    [ 7.500, 10.000) = 785 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     12.591 ms/op
     p(99.9900) =     27.659 ms/op
     p(99.9990) =     28.886 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.292 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.010 ms/op
Iteration   1: 3.640 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.274 ms/op
                 getUser·p0.999:  20.845 ms/op
                 getUser·p0.9999: 32.382 ms/op
                 getUser·p1.00:   33.358 ms/op

Iteration   2: 3.476 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.702 ms/op
                 getUser·p0.999:  21.726 ms/op
                 getUser·p0.9999: 26.975 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   3: 3.722 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.527 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  18.053 ms/op
                 getUser·p0.9999: 27.066 ms/op
                 getUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 265904
  mean =      3.610 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5032 
    [ 2.500,  5.000) = 247443 
    [ 5.000,  7.500) = 11248 
    [ 7.500, 10.000) = 1625 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     20.581 ms/op
     p(99.9900) =     30.815 ms/op
     p(99.9990) =     33.205 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.176 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.565 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.013 ms/op
Iteration   1: 4.247 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   6.185 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  20.559 ms/op
                 listUser·p0.9999: 40.401 ms/op
                 listUser·p1.00:   42.205 ms/op

Iteration   2: 4.062 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.503 ms/op
                 listUser·p0.999:  16.197 ms/op
                 listUser·p0.9999: 21.266 ms/op
                 listUser·p1.00:   23.855 ms/op

Iteration   3: 4.040 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.780 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   8.036 ms/op
                 listUser·p0.999:  15.299 ms/op
                 listUser·p0.9999: 18.317 ms/op
                 listUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233246
  mean =      4.114 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 220398 
    [ 5.000, 10.000) = 11742 
    [10.000, 15.000) = 721 
    [15.000, 20.000) = 247 
    [20.000, 25.000) = 106 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      8.073 ms/op
     p(99.9000) =     17.679 ms/op
     p(99.9900) =     37.072 ms/op
     p(99.9990) =     41.856 ms/op
     p(99.9999) =     42.205 ms/op
    p(100.0000) =     42.205 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.068 ± 4.786  ops/ms
ClientPb.existUser                       thrpt       3   9.618 ± 3.223  ops/ms
ClientPb.getUser                         thrpt       3   9.300 ± 2.897  ops/ms
ClientPb.listUser                        thrpt       3   7.926 ± 2.001  ops/ms
ClientPb.createUser                       avgt       3   3.486 ± 0.505   ms/op
ClientPb.existUser                        avgt       3   3.248 ± 0.711   ms/op
ClientPb.getUser                          avgt       3   3.508 ± 1.545   ms/op
ClientPb.listUser                         avgt       3   4.012 ± 0.643   ms/op
ClientPb.createUser                     sample  277484   3.458 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.030           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.529           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.612           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.312           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.523           ms/op
ClientPb.existUser                      sample  281840   3.406 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.210           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.301           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.234           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.591           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.659           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.000           ms/op
ClientPb.getUser                        sample  265904   3.610 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.999           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.428           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.149           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.022           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.581           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.815           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.358           ms/op
ClientPb.listUser                       sample  233246   4.114 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.421           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.145           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.073           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.679           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.072           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.205           ms/op
