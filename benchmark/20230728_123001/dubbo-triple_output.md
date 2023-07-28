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
# Warmup Iteration   1: 1.499 ops/ms
# Warmup Iteration   2: 3.478 ops/ms
# Warmup Iteration   3: 6.834 ops/ms
Iteration   1: 7.265 ops/ms
Iteration   2: 7.511 ops/ms
Iteration   3: 7.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.452 ±(99.9%) 3.011 ops/ms [Average]
  (min, avg, max) = (7.265, 7.452, 7.578), stdev = 0.165
  CI (99.9%): [4.440, 10.463] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.266 ops/ms
# Warmup Iteration   2: 6.281 ops/ms
# Warmup Iteration   3: 7.567 ops/ms
Iteration   1: 8.278 ops/ms
Iteration   2: 8.420 ops/ms
Iteration   3: 8.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.282 ±(99.9%) 2.479 ops/ms [Average]
  (min, avg, max) = (8.148, 8.282, 8.420), stdev = 0.136
  CI (99.9%): [5.803, 10.761] (assumes normal distribution)


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
# Warmup Iteration   1: 2.043 ops/ms
# Warmup Iteration   2: 6.536 ops/ms
# Warmup Iteration   3: 7.538 ops/ms
Iteration   1: 7.715 ops/ms
Iteration   2: 7.486 ops/ms
Iteration   3: 7.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.645 ±(99.9%) 2.516 ops/ms [Average]
  (min, avg, max) = (7.486, 7.645, 7.734), stdev = 0.138
  CI (99.9%): [5.129, 10.161] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 1.844 ops/ms
# Warmup Iteration   2: 4.896 ops/ms
# Warmup Iteration   3: 6.445 ops/ms
Iteration   1: 6.288 ops/ms
Iteration   2: 6.696 ops/ms
Iteration   3: 6.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.534 ±(99.9%) 3.948 ops/ms [Average]
  (min, avg, max) = (6.288, 6.534, 6.696), stdev = 0.216
  CI (99.9%): [2.586, 10.482] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 14.907 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.975 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.400 ±(99.9%) 0.007 ms/op
Iteration   1: 4.175 ±(99.9%) 0.006 ms/op
Iteration   2: 3.997 ±(99.9%) 0.013 ms/op
Iteration   3: 4.188 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.120 ±(99.9%) 1.947 ms/op [Average]
  (min, avg, max) = (3.997, 4.120, 4.188), stdev = 0.107
  CI (99.9%): [2.174, 6.067] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.699 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.560 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.023 ±(99.9%) 0.003 ms/op
Iteration   1: 4.062 ±(99.9%) 0.005 ms/op
Iteration   2: 3.928 ±(99.9%) 0.008 ms/op
Iteration   3: 4.006 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.998 ±(99.9%) 1.230 ms/op [Average]
  (min, avg, max) = (3.928, 3.998, 4.062), stdev = 0.067
  CI (99.9%): [2.768, 5.229] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 14.193 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.239 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.223 ±(99.9%) 0.013 ms/op
Iteration   1: 4.002 ±(99.9%) 0.008 ms/op
Iteration   2: 4.053 ±(99.9%) 0.008 ms/op
Iteration   3: 4.069 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.041 ±(99.9%) 0.638 ms/op [Average]
  (min, avg, max) = (4.002, 4.041, 4.069), stdev = 0.035
  CI (99.9%): [3.403, 4.679] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.112 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.805 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.867 ±(99.9%) 0.011 ms/op
Iteration   1: 4.750 ±(99.9%) 0.010 ms/op
Iteration   2: 4.641 ±(99.9%) 0.009 ms/op
Iteration   3: 4.856 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.749 ±(99.9%) 1.964 ms/op [Average]
  (min, avg, max) = (4.641, 4.749, 4.856), stdev = 0.108
  CI (99.9%): [2.785, 6.713] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.533 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 5.172 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.625 ±(99.9%) 0.020 ms/op
Iteration   1: 4.278 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.964 ms/op
                 createUser·p0.50:   4.129 ms/op
                 createUser·p0.90:   5.005 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   7.455 ms/op
                 createUser·p0.999:  11.772 ms/op
                 createUser·p0.9999: 28.133 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   2: 4.118 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   4.010 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  17.882 ms/op
                 createUser·p0.9999: 30.349 ms/op
                 createUser·p1.00:   32.047 ms/op

Iteration   3: 4.039 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.567 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   7.332 ms/op
                 createUser·p0.999:  29.295 ms/op
                 createUser·p0.9999: 33.162 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 231710
  mean =      4.143 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 193 
    [ 2.500,  5.000) = 215708 
    [ 5.000,  7.500) = 13784 
    [ 7.500, 10.000) = 1379 
    [10.000, 12.500) = 268 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 93 
    [30.000, 32.500) = 65 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.501 ms/op
     p(50.0000) =      4.010 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     25.063 ms/op
     p(99.9900) =     32.047 ms/op
     p(99.9990) =     34.123 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.988 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 4.663 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.012 ms/op
Iteration   1: 4.058 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.593 ms/op
                 existUser·p0.50:   3.916 ms/op
                 existUser·p0.90:   4.653 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   7.750 ms/op
                 existUser·p0.999:  23.042 ms/op
                 existUser·p0.9999: 25.927 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   2: 3.978 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   5.353 ms/op
                 existUser·p0.99:   7.184 ms/op
                 existUser·p0.999:  15.108 ms/op
                 existUser·p0.9999: 27.820 ms/op
                 existUser·p1.00:   29.065 ms/op

Iteration   3: 4.007 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.905 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   5.374 ms/op
                 existUser·p0.99:   8.438 ms/op
                 existUser·p0.999:  17.346 ms/op
                 existUser·p0.9999: 31.262 ms/op
                 existUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 239052
  mean =      4.014 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 178 
    [ 2.500,  5.000) = 223932 
    [ 5.000,  7.500) = 11812 
    [ 7.500, 10.000) = 2109 
    [10.000, 12.500) = 527 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      7.963 ms/op
     p(99.9000) =     17.857 ms/op
     p(99.9900) =     30.231 ms/op
     p(99.9990) =     34.210 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.255 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 4.999 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.014 ms/op
Iteration   1: 4.124 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.052 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   7.881 ms/op
                 getUser·p0.999:  12.239 ms/op
                 getUser·p0.9999: 26.869 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   2: 3.985 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.915 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  26.502 ms/op
                 getUser·p0.9999: 28.868 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   3: 4.002 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.167 ms/op
                 getUser·p0.50:   3.883 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.950 ms/op
                 getUser·p0.999:  13.365 ms/op
                 getUser·p0.9999: 32.145 ms/op
                 getUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237595
  mean =      4.036 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 227292 
    [ 5.000,  7.500) = 8114 
    [ 7.500, 10.000) = 1481 
    [10.000, 12.500) = 400 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.915 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     13.504 ms/op
     p(99.9900) =     30.031 ms/op
     p(99.9990) =     32.633 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.180 ±(99.9%) 0.233 ms/op
# Warmup Iteration   2: 5.958 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.814 ±(99.9%) 0.017 ms/op
Iteration   1: 4.959 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.019 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   9.622 ms/op
                 listUser·p0.999:  27.951 ms/op
                 listUser·p0.9999: 31.132 ms/op
                 listUser·p1.00:   39.059 ms/op

Iteration   2: 4.830 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  21.668 ms/op
                 listUser·p0.9999: 25.919 ms/op
                 listUser·p1.00:   26.706 ms/op

Iteration   3: 4.714 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.862 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  19.628 ms/op
                 listUser·p0.9999: 24.183 ms/op
                 listUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198631
  mean =      4.832 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 153475 
    [ 5.000,  7.500) = 40266 
    [ 7.500, 10.000) = 3385 
    [10.000, 12.500) = 756 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.862 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      9.404 ms/op
     p(99.9000) =     23.233 ms/op
     p(99.9900) =     30.217 ms/op
     p(99.9990) =     38.413 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.452 ± 3.011  ops/ms
ClientPb.existUser                       thrpt       3   8.282 ± 2.479  ops/ms
ClientPb.getUser                         thrpt       3   7.645 ± 2.516  ops/ms
ClientPb.listUser                        thrpt       3   6.534 ± 3.948  ops/ms
ClientPb.createUser                       avgt       3   4.120 ± 1.947   ms/op
ClientPb.existUser                        avgt       3   3.998 ± 1.230   ms/op
ClientPb.getUser                          avgt       3   4.041 ± 0.638   ms/op
ClientPb.listUser                         avgt       3   4.749 ± 1.964   ms/op
ClientPb.createUser                     sample  231710   4.143 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.501           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.735           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.299           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.063           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.047           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.275           ms/op
ClientPb.existUser                      sample  239052   4.014 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.524           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.555           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.963           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.857           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.231           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.406           ms/op
ClientPb.getUser                        sample  237595   4.036 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.915           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.866           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.299           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.504           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.031           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.801           ms/op
ClientPb.listUser                       sample  198631   4.832 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.862           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.333           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.816           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.404           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.233           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.217           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.059           ms/op
