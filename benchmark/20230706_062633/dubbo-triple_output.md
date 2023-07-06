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
# Warmup Iteration   1: 1.748 ops/ms
# Warmup Iteration   2: 4.164 ops/ms
# Warmup Iteration   3: 7.913 ops/ms
Iteration   1: 7.822 ops/ms
Iteration   2: 8.735 ops/ms
Iteration   3: 8.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.329 ±(99.9%) 8.486 ops/ms [Average]
  (min, avg, max) = (7.822, 8.329, 8.735), stdev = 0.465
  CI (99.9%): [≈ 0, 16.816] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.626 ops/ms
# Warmup Iteration   2: 7.514 ops/ms
# Warmup Iteration   3: 8.495 ops/ms
Iteration   1: 8.752 ops/ms
Iteration   2: 8.868 ops/ms
Iteration   3: 8.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.695 ±(99.9%) 3.769 ops/ms [Average]
  (min, avg, max) = (8.466, 8.695, 8.868), stdev = 0.207
  CI (99.9%): [4.926, 12.465] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.248 ops/ms
# Warmup Iteration   2: 7.034 ops/ms
# Warmup Iteration   3: 7.969 ops/ms
Iteration   1: 8.707 ops/ms
Iteration   2: 8.208 ops/ms
Iteration   3: 8.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.499 ±(99.9%) 4.735 ops/ms [Average]
  (min, avg, max) = (8.208, 8.499, 8.707), stdev = 0.260
  CI (99.9%): [3.764, 13.234] (assumes normal distribution)


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
# Warmup Iteration   1: 2.374 ops/ms
# Warmup Iteration   2: 6.330 ops/ms
# Warmup Iteration   3: 7.004 ops/ms
Iteration   1: 7.320 ops/ms
Iteration   2: 7.185 ops/ms
Iteration   3: 7.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.205 ±(99.9%) 1.948 ops/ms [Average]
  (min, avg, max) = (7.110, 7.205, 7.320), stdev = 0.107
  CI (99.9%): [5.257, 9.153] (assumes normal distribution)


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
# Warmup Iteration   1: 12.953 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.008 ms/op
Iteration   1: 3.837 ±(99.9%) 0.008 ms/op
Iteration   2: 3.749 ±(99.9%) 0.003 ms/op
Iteration   3: 3.688 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.758 ±(99.9%) 1.367 ms/op [Average]
  (min, avg, max) = (3.688, 3.758, 3.837), stdev = 0.075
  CI (99.9%): [2.391, 5.126] (assumes normal distribution)


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
# Warmup Iteration   1: 11.941 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.006 ms/op
Iteration   1: 3.570 ±(99.9%) 0.006 ms/op
Iteration   2: 3.621 ±(99.9%) 0.004 ms/op
Iteration   3: 3.559 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.584 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (3.559, 3.584, 3.621), stdev = 0.033
  CI (99.9%): [2.978, 4.189] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.337 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.005 ms/op
Iteration   1: 4.076 ±(99.9%) 0.008 ms/op
Iteration   2: 3.969 ±(99.9%) 0.006 ms/op
Iteration   3: 3.851 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.965 ±(99.9%) 2.053 ms/op [Average]
  (min, avg, max) = (3.851, 3.965, 4.076), stdev = 0.113
  CI (99.9%): [1.912, 6.019] (assumes normal distribution)


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
# Warmup Iteration   1: 13.663 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.794 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.524 ±(99.9%) 0.008 ms/op
Iteration   1: 4.432 ±(99.9%) 0.010 ms/op
Iteration   2: 4.306 ±(99.9%) 0.016 ms/op
Iteration   3: 4.435 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.391 ±(99.9%) 1.341 ms/op [Average]
  (min, avg, max) = (4.306, 4.391, 4.435), stdev = 0.073
  CI (99.9%): [3.051, 5.732] (assumes normal distribution)


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
# Warmup Iteration   1: 11.167 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.629 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.278 ±(99.9%) 0.019 ms/op
Iteration   1: 3.777 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.356 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.586 ms/op
                 createUser·p0.999:  9.961 ms/op
                 createUser·p0.9999: 28.738 ms/op
                 createUser·p1.00:   29.852 ms/op

Iteration   2: 3.763 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   6.832 ms/op
                 createUser·p0.999:  12.828 ms/op
                 createUser·p0.9999: 26.542 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   3: 3.719 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.370 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   6.406 ms/op
                 createUser·p0.999:  25.332 ms/op
                 createUser·p0.9999: 34.603 ms/op
                 createUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 255680
  mean =      3.753 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1246 
    [ 2.500,  5.000) = 245888 
    [ 5.000,  7.500) = 7023 
    [ 7.500, 10.000) = 1059 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.370 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     20.698 ms/op
     p(99.9900) =     33.012 ms/op
     p(99.9990) =     34.800 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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
# Warmup Iteration   1: 9.633 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.014 ms/op
Iteration   1: 3.578 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.563 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   6.390 ms/op
                 existUser·p0.999:  11.868 ms/op
                 existUser·p0.9999: 24.775 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   2: 3.675 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.692 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.981 ms/op
                 existUser·p0.99:   6.930 ms/op
                 existUser·p0.999:  24.370 ms/op
                 existUser·p0.9999: 30.310 ms/op
                 existUser·p1.00:   30.769 ms/op

Iteration   3: 3.458 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.780 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  8.602 ms/op
                 existUser·p0.9999: 29.811 ms/op
                 existUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 268945
  mean =      3.568 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7448 
    [ 2.500,  5.000) = 253177 
    [ 5.000,  7.500) = 7313 
    [ 7.500, 10.000) = 631 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 93 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.563 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     11.634 ms/op
     p(99.9900) =     29.757 ms/op
     p(99.9990) =     30.769 ms/op
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
# Warmup Iteration   1: 9.938 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.269 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.013 ms/op
Iteration   1: 3.742 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.618 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.084 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   7.766 ms/op
                 getUser·p0.999:  22.827 ms/op
                 getUser·p0.9999: 34.144 ms/op
                 getUser·p1.00:   35.455 ms/op

Iteration   2: 3.817 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   7.774 ms/op
                 getUser·p0.999:  11.583 ms/op
                 getUser·p0.9999: 27.185 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 3.965 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.354 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   7.336 ms/op
                 getUser·p0.999:  23.342 ms/op
                 getUser·p0.9999: 32.270 ms/op
                 getUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 249865
  mean =      3.839 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 910 
    [ 2.500,  5.000) = 237637 
    [ 5.000,  7.500) = 8295 
    [ 7.500, 10.000) = 2428 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.354 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     22.164 ms/op
     p(99.9900) =     33.031 ms/op
     p(99.9990) =     35.161 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


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
# Warmup Iteration   1: 12.872 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 5.181 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.542 ±(99.9%) 0.016 ms/op
Iteration   1: 4.437 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   4.276 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   8.241 ms/op
                 listUser·p0.999:  24.936 ms/op
                 listUser·p0.9999: 30.510 ms/op
                 listUser·p1.00:   31.556 ms/op

Iteration   2: 4.400 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   4.293 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   8.135 ms/op
                 listUser·p0.999:  16.515 ms/op
                 listUser·p0.9999: 18.455 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   3: 4.465 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   7.987 ms/op
                 listUser·p0.999:  16.712 ms/op
                 listUser·p0.9999: 20.356 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 216313
  mean =      4.434 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 200490 
    [ 5.000,  7.500) = 12310 
    [ 7.500, 10.000) = 2655 
    [10.000, 12.500) = 336 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     28.303 ms/op
     p(99.9990) =     31.457 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.329 ± 8.486  ops/ms
ClientPb.existUser                       thrpt       3   8.695 ± 3.769  ops/ms
ClientPb.getUser                         thrpt       3   8.499 ± 4.735  ops/ms
ClientPb.listUser                        thrpt       3   7.205 ± 1.948  ops/ms
ClientPb.createUser                       avgt       3   3.758 ± 1.367   ms/op
ClientPb.existUser                        avgt       3   3.584 ± 0.606   ms/op
ClientPb.getUser                          avgt       3   3.965 ± 2.053   ms/op
ClientPb.listUser                         avgt       3   4.391 ± 1.341   ms/op
ClientPb.createUser                     sample  255680   3.753 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.370           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.650           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.611           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.698           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.012           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.865           ms/op
ClientPb.existUser                      sample  268945   3.568 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.563           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.498           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.018           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.497           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.332           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.634           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.757           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.031           ms/op
ClientPb.getUser                        sample  249865   3.839 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.354           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.891           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.692           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.164           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.031           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.455           ms/op
ClientPb.listUser                       sample  216313   4.434 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.341           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.866           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.226           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.126           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.022           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.303           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.556           ms/op
