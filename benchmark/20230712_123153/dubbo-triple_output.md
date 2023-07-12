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
# Warmup Iteration   1: 1.032 ops/ms
# Warmup Iteration   2: 2.072 ops/ms
# Warmup Iteration   3: 4.623 ops/ms
Iteration   1: 5.090 ops/ms
Iteration   2: 5.485 ops/ms
Iteration   3: 5.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.353 ±(99.9%) 4.160 ops/ms [Average]
  (min, avg, max) = (5.090, 5.353, 5.485), stdev = 0.228
  CI (99.9%): [1.193, 9.512] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:19
# Fork: 1 of 1
# Warmup Iteration   1: 1.382 ops/ms
# Warmup Iteration   2: 3.694 ops/ms
# Warmup Iteration   3: 5.152 ops/ms
Iteration   1: 5.719 ops/ms
Iteration   2: 5.795 ops/ms
Iteration   3: 5.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.672 ±(99.9%) 2.786 ops/ms [Average]
  (min, avg, max) = (5.501, 5.672, 5.795), stdev = 0.153
  CI (99.9%): [2.886, 8.457] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.470 ops/ms
# Warmup Iteration   2: 3.809 ops/ms
# Warmup Iteration   3: 5.447 ops/ms
Iteration   1: 5.386 ops/ms
Iteration   2: 5.324 ops/ms
Iteration   3: 5.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.381 ±(99.9%) 0.996 ops/ms [Average]
  (min, avg, max) = (5.324, 5.381, 5.433), stdev = 0.055
  CI (99.9%): [4.385, 6.376] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.318 ops/ms
# Warmup Iteration   2: 3.172 ops/ms
# Warmup Iteration   3: 4.423 ops/ms
Iteration   1: 4.615 ops/ms
Iteration   2: 4.385 ops/ms
Iteration   3: 4.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.551 ±(99.9%) 2.649 ops/ms [Average]
  (min, avg, max) = (4.385, 4.551, 4.653), stdev = 0.145
  CI (99.9%): [1.902, 7.199] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 21.025 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 7.829 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.183 ±(99.9%) 0.012 ms/op
Iteration   1: 5.935 ±(99.9%) 0.018 ms/op
Iteration   2: 5.745 ±(99.9%) 0.010 ms/op
Iteration   3: 5.743 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.808 ±(99.9%) 2.015 ms/op [Average]
  (min, avg, max) = (5.743, 5.808, 5.935), stdev = 0.110
  CI (99.9%): [3.792, 7.823] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 18.687 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 6.860 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.805 ±(99.9%) 0.007 ms/op
Iteration   1: 5.743 ±(99.9%) 0.011 ms/op
Iteration   2: 5.553 ±(99.9%) 0.016 ms/op
Iteration   3: 5.580 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.625 ±(99.9%) 1.874 ms/op [Average]
  (min, avg, max) = (5.553, 5.625, 5.743), stdev = 0.103
  CI (99.9%): [3.752, 7.499] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:41
# Fork: 1 of 1
# Warmup Iteration   1: 20.230 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 9.811 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.084 ±(99.9%) 0.015 ms/op
Iteration   1: 5.939 ±(99.9%) 0.017 ms/op
Iteration   2: 5.846 ±(99.9%) 0.017 ms/op
Iteration   3: 6.063 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.949 ±(99.9%) 1.993 ms/op [Average]
  (min, avg, max) = (5.846, 5.949, 6.063), stdev = 0.109
  CI (99.9%): [3.956, 7.943] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:34
# Fork: 1 of 1
# Warmup Iteration   1: 24.674 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 8.588 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 7.036 ±(99.9%) 0.016 ms/op
Iteration   1: 7.329 ±(99.9%) 0.015 ms/op
Iteration   2: 6.850 ±(99.9%) 0.019 ms/op
Iteration   3: 6.855 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.011 ±(99.9%) 5.023 ms/op [Average]
  (min, avg, max) = (6.850, 7.011, 7.329), stdev = 0.275
  CI (99.9%): [1.988, 12.034] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:27
# Fork: 1 of 1
# Warmup Iteration   1: 19.885 ±(99.9%) 0.386 ms/op
# Warmup Iteration   2: 7.775 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.250 ±(99.9%) 0.027 ms/op
Iteration   1: 5.885 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.535 ms/op
                 createUser·p0.50:   5.587 ms/op
                 createUser·p0.90:   7.234 ms/op
                 createUser·p0.95:   8.167 ms/op
                 createUser·p0.99:   10.928 ms/op
                 createUser·p0.999:  18.717 ms/op
                 createUser·p0.9999: 29.743 ms/op
                 createUser·p1.00:   30.081 ms/op

Iteration   2: 6.100 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.655 ms/op
                 createUser·p0.50:   5.906 ms/op
                 createUser·p0.90:   7.406 ms/op
                 createUser·p0.95:   8.069 ms/op
                 createUser·p0.99:   9.929 ms/op
                 createUser·p0.999:  29.672 ms/op
                 createUser·p0.9999: 33.260 ms/op
                 createUser·p1.00:   34.013 ms/op

Iteration   3: 5.785 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.712 ms/op
                 createUser·p0.50:   5.464 ms/op
                 createUser·p0.90:   6.971 ms/op
                 createUser·p0.95:   7.782 ms/op
                 createUser·p0.99:   11.010 ms/op
                 createUser·p0.999:  29.810 ms/op
                 createUser·p0.9999: 32.947 ms/op
                 createUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 162143
  mean =      5.920 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 28415 
    [ 5.000,  7.500) = 121331 
    [ 7.500, 10.000) = 10159 
    [10.000, 12.500) = 1520 
    [12.500, 15.000) = 386 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 77 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.655 ms/op
     p(50.0000) =      5.644 ms/op
     p(90.0000) =      7.225 ms/op
     p(95.0000) =      8.020 ms/op
     p(99.0000) =     10.633 ms/op
     p(99.9000) =     23.490 ms/op
     p(99.9900) =     32.768 ms/op
     p(99.9990) =     33.932 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 18.858 ±(99.9%) 0.321 ms/op
# Warmup Iteration   2: 6.645 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.816 ±(99.9%) 0.023 ms/op
Iteration   1: 5.942 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.507 ms/op
                 existUser·p0.50:   5.562 ms/op
                 existUser·p0.90:   7.619 ms/op
                 existUser·p0.95:   8.831 ms/op
                 existUser·p0.99:   11.731 ms/op
                 existUser·p0.999:  15.361 ms/op
                 existUser·p0.9999: 26.689 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   2: 5.870 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   2.372 ms/op
                 existUser·p0.50:   5.431 ms/op
                 existUser·p0.90:   7.569 ms/op
                 existUser·p0.95:   8.749 ms/op
                 existUser·p0.99:   11.747 ms/op
                 existUser·p0.999:  31.392 ms/op
                 existUser·p0.9999: 39.634 ms/op
                 existUser·p1.00:   40.239 ms/op

Iteration   3: 5.883 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.564 ms/op
                 existUser·p0.50:   5.521 ms/op
                 existUser·p0.90:   7.250 ms/op
                 existUser·p0.95:   8.356 ms/op
                 existUser·p0.99:   12.157 ms/op
                 existUser·p0.999:  31.653 ms/op
                 existUser·p0.9999: 36.128 ms/op
                 existUser·p1.00:   37.093 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 162601
  mean =      5.898 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 35578 
    [ 5.000, 10.000) = 123375 
    [10.000, 15.000) = 3065 
    [15.000, 20.000) = 351 
    [20.000, 25.000) = 72 
    [25.000, 30.000) = 33 
    [30.000, 35.000) = 81 
    [35.000, 40.000) = 43 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.372 ms/op
     p(50.0000) =      5.497 ms/op
     p(90.0000) =      7.479 ms/op
     p(95.0000) =      8.684 ms/op
     p(99.0000) =     11.813 ms/op
     p(99.9000) =     24.969 ms/op
     p(99.9900) =     38.142 ms/op
     p(99.9990) =     40.239 ms/op
     p(99.9999) =     40.239 ms/op
    p(100.0000) =     40.239 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.344 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 7.217 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.023 ±(99.9%) 0.023 ms/op
Iteration   1: 5.765 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.753 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   6.906 ms/op
                 getUser·p0.95:   7.979 ms/op
                 getUser·p0.99:   10.797 ms/op
                 getUser·p0.999:  24.819 ms/op
                 getUser·p0.9999: 27.015 ms/op
                 getUser·p1.00:   27.787 ms/op

Iteration   2: 5.949 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.499 ms/op
                 getUser·p0.50:   5.669 ms/op
                 getUser·p0.90:   7.062 ms/op
                 getUser·p0.95:   8.389 ms/op
                 getUser·p0.99:   11.401 ms/op
                 getUser·p0.999:  18.776 ms/op
                 getUser·p0.9999: 28.365 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   3: 5.902 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.858 ms/op
                 getUser·p0.50:   5.652 ms/op
                 getUser·p0.90:   6.963 ms/op
                 getUser·p0.95:   7.881 ms/op
                 getUser·p0.99:   10.769 ms/op
                 getUser·p0.999:  27.710 ms/op
                 getUser·p0.9999: 34.445 ms/op
                 getUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 163558
  mean =      5.871 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 26232 
    [ 5.000,  7.500) = 126001 
    [ 7.500, 10.000) = 8595 
    [10.000, 12.500) = 1738 
    [12.500, 15.000) = 563 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.858 ms/op
     p(50.0000) =      5.595 ms/op
     p(90.0000) =      6.980 ms/op
     p(95.0000) =      8.028 ms/op
     p(99.0000) =     10.895 ms/op
     p(99.9000) =     24.347 ms/op
     p(99.9900) =     32.450 ms/op
     p(99.9990) =     35.151 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 20.573 ±(99.9%) 0.354 ms/op
# Warmup Iteration   2: 8.562 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 7.282 ±(99.9%) 0.033 ms/op
Iteration   1: 6.862 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.191 ms/op
                 listUser·p0.50:   6.447 ms/op
                 listUser·p0.90:   8.421 ms/op
                 listUser·p0.95:   9.634 ms/op
                 listUser·p0.99:   12.537 ms/op
                 listUser·p0.999:  30.835 ms/op
                 listUser·p0.9999: 33.303 ms/op
                 listUser·p1.00:   34.210 ms/op

Iteration   2: 6.972 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.683 ms/op
                 listUser·p0.50:   6.595 ms/op
                 listUser·p0.90:   8.389 ms/op
                 listUser·p0.95:   9.830 ms/op
                 listUser·p0.99:   12.534 ms/op
                 listUser·p0.999:  34.351 ms/op
                 listUser·p0.9999: 39.704 ms/op
                 listUser·p1.00:   40.501 ms/op

Iteration   3: 7.023 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   6.742 ms/op
                 listUser·p0.90:   8.208 ms/op
                 listUser·p0.95:   9.224 ms/op
                 listUser·p0.99:   12.280 ms/op
                 listUser·p0.999:  31.946 ms/op
                 listUser·p0.9999: 35.084 ms/op
                 listUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 138068
  mean =      6.952 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1642 
    [ 5.000, 10.000) = 131005 
    [10.000, 15.000) = 4914 
    [15.000, 20.000) = 205 
    [20.000, 25.000) = 14 
    [25.000, 30.000) = 46 
    [30.000, 35.000) = 199 
    [35.000, 40.000) = 41 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.404 ms/op
     p(50.0000) =      6.603 ms/op
     p(90.0000) =      8.331 ms/op
     p(95.0000) =      9.568 ms/op
     p(99.0000) =     12.473 ms/op
     p(99.9000) =     32.145 ms/op
     p(99.9900) =     38.178 ms/op
     p(99.9990) =     40.451 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


# Run complete. Total time: 00:13:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.353 ± 4.160  ops/ms
ClientPb.existUser                       thrpt       3   5.672 ± 2.786  ops/ms
ClientPb.getUser                         thrpt       3   5.381 ± 0.996  ops/ms
ClientPb.listUser                        thrpt       3   4.551 ± 2.649  ops/ms
ClientPb.createUser                       avgt       3   5.808 ± 2.015   ms/op
ClientPb.existUser                        avgt       3   5.625 ± 1.874   ms/op
ClientPb.getUser                          avgt       3   5.949 ± 1.993   ms/op
ClientPb.listUser                         avgt       3   7.011 ± 5.023   ms/op
ClientPb.createUser                     sample  162143   5.920 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.655           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.644           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.020           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.633           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.490           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.768           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.013           ms/op
ClientPb.existUser                      sample  162601   5.898 ± 0.014   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.372           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.497           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.479           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.684           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.813           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.969           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.142           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.239           ms/op
ClientPb.getUser                        sample  163558   5.871 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.858           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.595           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.980           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.028           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.895           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.347           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.450           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.193           ms/op
ClientPb.listUser                       sample  138068   6.952 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.404           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.603           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.331           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.568           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.473           ms/op
ClientPb.listUser:listUser·p0.999       sample          32.145           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.178           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.501           ms/op
